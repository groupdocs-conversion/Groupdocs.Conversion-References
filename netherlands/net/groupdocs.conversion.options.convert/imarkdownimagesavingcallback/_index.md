---
title: "IMarkdownImageSavingCallback"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Verwerkt aangepaste verwerking van afbeeldingen tijdens het opslaan naar Markdown. Eenmaal per afbeelding aangeroepen om MarkdownImageSavingArgs./markdownimagesavingargs te muteren om de URI die in de Markdown-uitvoer is ingebed te beheersen en/of om te bepalen waar de afbeeldingsbytes worden geschreven."
type: docs
weight: 1870
url: /nl/net/groupdocs.conversion.options.convert/imarkdownimagesavingcallback/
---
## IMarkdownImageSavingCallback interface

Verwerkt aangepaste verwerking van afbeeldingen tijdens het opslaan naar Markdown. Eenmaal per afbeelding aangeroepen; muteren [`MarkdownImageSavingArgs`](../markdownimagesavingargs) om de URI die in de Markdown-uitvoer is ingebed te beheersen en/of om te bepalen waar de afbeeldingsbytes worden geschreven.

```csharp
public interface IMarkdownImageSavingCallback
```

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [ImageSaving](../../groupdocs.conversion.options.convert/imarkdownimagesavingcallback/imagesaving)(MarkdownImageSavingArgs) | Aangeroepen voor elke afbeelding die naar het Markdown‑document wordt geschreven. |

### Voorbeelden

Scenario 1 — capture afbeeldingsbytes in het geheugen en embed placeholder‑ids (handig wanneer de aanroeper afbeeldingen elders wil opslaan of ze wil nabewerken):

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
    // captured["image0"], captured["image1"], ... bevatten nu de afbeeldingsbytes
}
finally
{
    foreach (var s in captured.Values) s.Dispose();  // caller owns the streams
}
```

Scenario 2 — bewaar afbeeldingen op schijf naast het .md‑bestand en verwijs ernaar via de bestandsnaam:

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
        // KeepImageStreamOpen blijft op standaard (false) → de converter leegt en sluit het bestand.
    }
}

var options = new WordProcessingConvertOptions { Format = WordProcessingFileType.Md };
options.MarkdownOptions.ImageSavingCallback = new FileImagesCallback("./out");

using var converter = new Converter("source.pdf");
converter.Convert("./out/output.md", options);
// ./out/image0.png, ./out/image1.png, ... worden door de converter geschreven en gesloten.
```

### Zie ook

* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
