---
title: "IMarkdownImageSavingCallback"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Gestisce l'elaborazione personalizzata delle immagini durante il salvataggio in Markdown. Invocata una volta per immagine per modificare MarkdownImageSavingArgs./markdownimagesavingargs per controllare l'URI incorporato nell'output Markdown e/o reindirizzare dove vengono scritti i byte dell'immagine."
type: docs
weight: 1870
url: /it/net/groupdocs.conversion.options.convert/imarkdownimagesavingcallback/
---
## IMarkdownImageSavingCallback interface

Gestisce l'elaborazione personalizzata delle immagini durante il salvataggio in Markdown. Invocata una volta per immagine; modifica [`MarkdownImageSavingArgs`](../markdownimagesavingargs) per controllare l'URI incorporato nell'output Markdown e/o reindirizzare dove vengono scritti i byte dell'immagine.

```csharp
public interface IMarkdownImageSavingCallback
```

## Vedi anche

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [ImageSaving](../../groupdocs.conversion.options.convert/imarkdownimagesavingcallback/imagesaving)(MarkdownImageSavingArgs) | Chiamata per ogni immagine scritta nel documento Markdown. |

### Esempi

Scenario 1 — cattura i byte dell'immagine in memoria e incorpora ID segnaposto (utile quando il chiamante desidera archiviare le immagini altrove o post‑processarle):

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
    // captured[\"image0\"], captured[\"image1\"], ... ora contengono i byte dell'immagine
}
finally
{
    foreach (var s in captured.Values) s.Dispose();  // caller owns the streams
}
```

Scenario 2 — persiste le immagini su disco accanto al file .md e le riferisce per nome file:

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
        // KeepImageStreamOpen lasciato al valore predefinito (false) → il convertitore svuota e chiude il file.
    }
}

var options = new WordProcessingConvertOptions { Format = WordProcessingFileType.Md };
options.MarkdownOptions.ImageSavingCallback = new FileImagesCallback("./out");

using var converter = new Converter("source.pdf");
converter.Convert("./out/output.md", options);
// ./out/image0.png, ./out/image1.png, ... sono scritti e chiusi dal convertitore.
```

### IConversionConvertOptions

* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
