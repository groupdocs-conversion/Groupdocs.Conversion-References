---
title: "IMarkdownImageSavingCallback"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "在保存为 Markdown 时处理图像的自定义处理。每个图像调用一次，修改 MarkdownImageSavingArgs./markdownimagesavingargs 以控制嵌入 Markdown 输出的 URI 和/或重定向图像字节的写入位置。"
type: docs
weight: 1870
url: /zh/net/groupdocs.conversion.options.convert/imarkdownimagesavingcallback/
---
## IMarkdownImageSavingCallback interface

在保存为 Markdown 时处理图像的自定义处理。每个图像调用一次；修改 [`MarkdownImageSavingArgs`](../markdownimagesavingargs) 以控制嵌入 Markdown 输出的 URI 和/或重定向图像字节的写入位置。

```csharp
public interface IMarkdownImageSavingCallback
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [ImageSaving](../../groupdocs.conversion.options.convert/imarkdownimagesavingcallback/imagesaving)(MarkdownImageSavingArgs) | 在每个图像写入 Markdown 文档时被调用。 |

### 示例

场景 1 — 在内存中捕获图像字节并嵌入占位符 ID（当调用者想将图像存储在其他位置或进行后处理时很有用）：

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
    // captured["image0"], captured["image1"], ... 现在保存了图像字节
}
finally
{
    foreach (var s in captured.Values) s.Dispose();  // caller owns the streams
}
```

场景 2 — 将图像持久化到与 .md 同目录的磁盘上，并通过文件名引用它们：

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
        // KeepImageStreamOpen 保持默认值 (false) → 转换器会刷新并关闭文件。
    }
}

var options = new WordProcessingConvertOptions { Format = WordProcessingFileType.Md };
options.MarkdownOptions.ImageSavingCallback = new FileImagesCallback("./out");

using var converter = new Converter("source.pdf");
converter.Convert("./out/output.md", options);
// ./out/image0.png, ./out/image1.png, ... 由转换器写入并关闭。
```

### 另见

* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
