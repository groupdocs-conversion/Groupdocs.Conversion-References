---
title: "IMarkdownImageSavingCallback"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Hantera anpassad bearbetning av bilder när de sparas till Markdown. Anropas en gång per bild för att förändra `MarkdownImageSavingArgs`/`markdownimagesavingargs` för att kontrollera den URI som bäddas in i Markdown-utdata och/eller omdirigera var bildbytarna skrivs."
type: docs
weight: 1870
url: /sv/net/groupdocs.conversion.options.convert/imarkdownimagesavingcallback/
---
## IMarkdownImageSavingCallback interface

Hantera anpassad bearbetning av bilder när de sparas till Markdown. Anropas en gång per bild; förändra [`MarkdownImageSavingArgs`](../markdownimagesavingargs) för att kontrollera den URI som bäddas in i Markdown-utdata och/eller omdirigera var bildbytarna skrivs.

```csharp
public interface IMarkdownImageSavingCallback
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [ImageSaving](../../groupdocs.conversion.options.convert/imarkdownimagesavingcallback/imagesaving)(MarkdownImageSavingArgs) | Kallas för varje bild som skrivs till Markdown-dokumentet. |

### Exempel

Scenario 1 — fånga bildbytarna i minnet och bädda in platshållar‑ID:n (användbart när anroparen vill lagra bilder någon annanstans eller efterbearbeta dem):

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
    // captured[\"image0\"], captured[\"image1\"], ... innehåller nu bildbytarna
}
finally
{
    foreach (var s in captured.Values) s.Dispose();  // caller owns the streams
}
```

Scenario 2 — spara bilder på disk tillsammans med .md-filen och referera till dem med filnamnet:

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
        // KeepImageStreamOpen lämnas på standardvärdet (false) → konverteraren spolar och stänger filen.
    }
}

var options = new WordProcessingConvertOptions { Format = WordProcessingFileType.Md };
options.MarkdownOptions.ImageSavingCallback = new FileImagesCallback("./out");

using var converter = new Converter("source.pdf");
converter.Convert("./out/output.md", options);
// ./out/image0.png, ./out/image1.png, ... skrivs och stängs av konverteraren.
```

### Se även

* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
