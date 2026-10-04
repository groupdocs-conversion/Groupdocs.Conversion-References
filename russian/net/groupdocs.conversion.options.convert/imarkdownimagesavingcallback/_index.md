---
title: "IMarkdownImageSavingCallback"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Обрабатывает пользовательскую обработку изображений при сохранении в Markdown. Вызывается один раз для каждого изображения, изменяя MarkdownImageSavingArgs./markdownimagesavingargs для управления URI, встроенным в вывод Markdown, и/или перенаправления места записи байтов изображения."
type: docs
weight: 1870
url: /ru/net/groupdocs.conversion.options.convert/imarkdownimagesavingcallback/
---
## IMarkdownImageSavingCallback interface

Обрабатывает пользовательскую обработку изображений при сохранении в Markdown. Вызывается один раз для каждого изображения; измените [`MarkdownImageSavingArgs`](../markdownimagesavingargs), чтобы управлять URI, встроенным в вывод Markdown, и/или перенаправить место записи байтов изображения.

```csharp
public interface IMarkdownImageSavingCallback
```

## Методы

| Имя | Описание |
| --- | --- |
| [ImageSaving](../../groupdocs.conversion.options.convert/imarkdownimagesavingcallback/imagesaving)(MarkdownImageSavingArgs) | Вызывается для каждого изображения, записываемого в документ Markdown. |

### Примеры

Сценарий 1 — захватить байты изображения в памяти и встроить идентификаторы-заполнители (полезно, когда вызывающий код хочет хранить изображения в другом месте или выполнять их последующую обработку):

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
    // captured[\"image0\"], captured[\"image1\"], ... теперь содержат байты изображения
}
finally
{
    foreach (var s in captured.Values) s.Dispose();  // caller owns the streams
}
```

Сценарий 2 — сохранить изображения на диск рядом с файлом .md и ссылаться на них по имени файла:

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
        // KeepImageStreamOpen оставлен по умолчанию (false) → конвертер сбрасывает буфер и закрывает файл.
    }
}

var options = new WordProcessingConvertOptions { Format = WordProcessingFileType.Md };
options.MarkdownOptions.ImageSavingCallback = new FileImagesCallback("./out");

using var converter = new Converter("source.pdf");
converter.Convert("./out/output.md", options);
// ./out/image0.png, ./out/image1.png, ... записываются и закрываются конвертером.
```

### См. также

* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
