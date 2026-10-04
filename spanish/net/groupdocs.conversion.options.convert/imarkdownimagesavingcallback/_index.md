---
title: "IMarkdownImageSavingCallback"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Gestiona el procesamiento personalizado de imágenes al guardar en Markdown. Se invoca una vez por imagen para mutar MarkdownImageSavingArgs./markdownimagesavingargs y controlar el URI incrustado en la salida Markdown y/o redirigir dónde se escriben los bytes de la imagen."
type: docs
weight: 1870
url: /es/net/groupdocs.conversion.options.convert/imarkdownimagesavingcallback/
---
## IMarkdownImageSavingCallback interface

Gestiona el procesamiento personalizado de imágenes al guardar en Markdown. Se invoca una vez por imagen; muta [`MarkdownImageSavingArgs`](../markdownimagesavingargs) para controlar el URI incrustado en la salida Markdown y/o redirigir dónde se escriben los bytes de la imagen.

```csharp
public interface IMarkdownImageSavingCallback
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [ImageSaving](../../groupdocs.conversion.options.convert/imarkdownimagesavingcallback/imagesaving)(MarkdownImageSavingArgs) | Se llama para cada imagen que se escribe en el documento Markdown. |

### Ejemplos

Escenario 1 — capturar los bytes de la imagen en memoria e incrustar identificadores de marcador de posición (útil cuando el llamador desea almacenar las imágenes en otro lugar o procesarlas posteriormente):

```csharp
class CaptureImagesCallback : IMarkdownImageSavingCallback
{
    private int _index;
    private readonly Dictionary<string, MemoryStream> _images;

    public CaptureImagesCallback(Dictionary<string, MemoryStream> images) => _images = images;

    public void ImageSaving(MarkdownImageSavingArgs args)
    {
        var id = $"image{_index++}";
        var buffer = new MemoryStream();
        _images[id] = buffer;
        args.ImageStream = buffer;            // redirect image bytes into our buffer
        args.ImageFileName = id;              // placeholder URI written into the .md
        args.KeepImageStreamOpen = true;      // keep buffer readable after Convert() returns
    }
}

var captured = new Dictionary<string, MemoryStream>();
try
{
    var options = new WordProcessingConvertOptions { Format = WordProcessingFileType.Md };
    options.MarkdownOptions.ImageSavingCallback = new CaptureImagesCallback(captured);

    using var converter = new Converter("source.pdf");
    converter.Convert("output.md", options);
    // captured[\"image0\"], captured[\"image1\"], ... ahora contienen los bytes de la imagen
}
finally
{
    foreach (var s in captured.Values) s.Dispose();  // caller owns the streams
}
```

Escenario 2 — persistir las imágenes en disco junto al .md y referenciarlas por nombre de archivo:

```csharp
class FileImagesCallback : IMarkdownImageSavingCallback
{
    private readonly string _outputFolder;
    private int _index;

    public FileImagesCallback(string outputFolder) => _outputFolder = outputFolder;

    public void ImageSaving(MarkdownImageSavingArgs args)
    {
        var fileName = $"image{_index++}.png";
        args.ImageStream = new FileStream(Path.Combine(_outputFolder, fileName), FileMode.Create);
        args.ImageFileName = fileName;        // written into the .md as ![](image0.png)
        // KeepImageStreamOpen se dejó en el valor predeterminado (false) → el convertidor vacía y cierra el archivo.
    }
}

var options = new WordProcessingConvertOptions { Format = WordProcessingFileType.Md };
options.MarkdownOptions.ImageSavingCallback = new FileImagesCallback("./out");

using var converter = new Converter("source.pdf");
converter.Convert("./out/output.md", options);
// ./out/image0.png, ./out/image1.png, ... son escritos y cerrados por el convertidor.
```

### Ver también

* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
