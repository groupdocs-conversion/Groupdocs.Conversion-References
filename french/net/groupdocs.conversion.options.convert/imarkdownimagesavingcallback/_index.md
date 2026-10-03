---
title: "IMarkdownImageSavingCallback"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Gère le traitement personnalisé des images lors de l'enregistrement au format Markdown. Appelé une fois par image pour modifier MarkdownImageSavingArgs./markdownimagesavingargs afin de contrôler l'URI intégré dans la sortie Markdown et/ou rediriger l'endroit où les octets d'image sont écrits."
type: docs
weight: 1870
url: /fr/net/groupdocs.conversion.options.convert/imarkdownimagesavingcallback/
---
## IMarkdownImageSavingCallback interface

Gère le traitement personnalisé des images lors de l'enregistrement au format Markdown. Appelé une fois par image ; modifiez [`MarkdownImageSavingArgs`](../markdownimagesavingargs) pour contrôler l'URI intégré dans la sortie Markdown et/ou rediriger l'endroit où les octets d'image sont écrits.

```csharp
public interface IMarkdownImageSavingCallback
```

## Méthodes

| Nom | Description |
| --- | --- |
| [ImageSaving](../../groupdocs.conversion.options.convert/imarkdownimagesavingcallback/imagesaving)(MarkdownImageSavingArgs) | Appelé pour chaque image écrite dans le document Markdown. |

### Exemples

Scénario 1 — capturer les octets d'image en mémoire et intégrer des identifiants de substitution (utile lorsque l'appelant souhaite stocker les images ailleurs ou les post‑traiter) :

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
    // captured["image0"], captured["image1"], ... contiennent maintenant les octets d'image
}
finally
{
    foreach (var s in captured.Values) s.Dispose();  // caller owns the streams
}
```

Scénario 2 — persister les images sur le disque à côté du .md et les référencer par nom de fichier :

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
        // KeepImageStreamOpen laissé à la valeur par défaut (false) → le convertisseur vide et ferme le fichier.
    }
}

var options = new WordProcessingConvertOptions { Format = WordProcessingFileType.Md };
options.MarkdownOptions.ImageSavingCallback = new FileImagesCallback("./out");

using var converter = new Converter("source.pdf");
converter.Convert("./out/output.md", options);
// ./out/image0.png, ./out/image1.png, ... sont écrits et fermés par le convertisseur.
```

### Voir aussi

* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
