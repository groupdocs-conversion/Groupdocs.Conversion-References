---
title: "IMarkdownImageSavingCallback"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Menangani pemrosesan khusus gambar saat menyimpan ke Markdown. Dipanggil sekali per gambar untuk memodifikasi MarkdownImageSavingArgs./markdownimagesavingargs guna mengontrol URI yang disematkan dalam output Markdown dan/atau mengarahkan ke mana byte gambar ditulis."
type: docs
weight: 1870
url: /id/net/groupdocs.conversion.options.convert/imarkdownimagesavingcallback/
---
## IMarkdownImageSavingCallback interface

Menangani pemrosesan khusus gambar saat menyimpan ke Markdown. Dipanggil sekali per gambar; ubah [`MarkdownImageSavingArgs`](../markdownimagesavingargs) untuk mengontrol URI yang disematkan dalam output Markdown dan/atau mengarahkan ke mana byte gambar ditulis.

```csharp
public interface IMarkdownImageSavingCallback
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| [ImageSaving](../../groupdocs.conversion.options.convert/imarkdownimagesavingcallback/imagesaving)(MarkdownImageSavingArgs) | Dipanggil untuk setiap gambar yang ditulis ke dokumen Markdown. |

### Contoh

Skenario 1 — tangkap byte gambar dalam memori dan sematkan id placeholder (berguna ketika pemanggil ingin menyimpan gambar di tempat lain atau memprosesnya setelahnya):

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
    // captured[\"image0\"], captured[\"image1\"], ... sekarang menyimpan byte gambar
}
finally
{
    foreach (var s in captured.Values) s.Dispose();  // caller owns the streams
}
```

Skenario 2 — simpan gambar ke disk bersamaan dengan .md dan referensikan mereka dengan nama file:

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
        // KeepImageStreamOpen dibiarkan pada nilai default (false) → konverter membersihkan dan menutup file.
    }
}

var options = new WordProcessingConvertOptions { Format = WordProcessingFileType.Md };
options.MarkdownOptions.ImageSavingCallback = new FileImagesCallback("./out");

using var converter = new Converter("source.pdf");
converter.Convert("./out/output.md", options);
// ./out/image0.png, ./out/image1.png, ... ditulis dan ditutup oleh konverter.
```

### Lihat Juga

* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
