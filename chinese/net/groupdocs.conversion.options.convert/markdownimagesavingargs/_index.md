---
title: "MarkdownImageSavingArgs"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "传递给 ImageSaving./imarkdownimagesavingcallback/imagesaving 的参数。"
type: docs
weight: 2000
url: /zh/net/groupdocs.conversion.options.convert/markdownimagesavingargs/
---
## MarkdownImageSavingArgs class

传递给 [`ImageSaving`](../imarkdownimagesavingcallback/imagesaving) 的参数。

```csharp
public sealed class MarkdownImageSavingArgs
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [ImageFileName](../../groupdocs.conversion.options.convert/markdownimagesavingargs/imagefilename) { get; set; } | 文件名（或占位符 ID）嵌入为 Markdown 输出中的图像 URI。赋值以重写该 URI。 |
| [ImageStream](../../groupdocs.conversion.options.convert/markdownimagesavingargs/imagestream) { get; set; } | 转换器将在此回调返回后写入图像字节的目标流。将其替换为您自己的可写流（例如用于磁盘持久化的 FileStream 或您打算随后读取的 MemoryStream）。 |
| [KeepImageStreamOpen](../../groupdocs.conversion.options.convert/markdownimagesavingargs/keepimagestreamopen) { get; set; } | 当为 false（默认）时，转换器在写入后关闭 [`ImageStream`](./imagestream)——这符合应刷新到磁盘的 FileStream 替代品的惯用做法。设为 true 可在转换完成后保持流打开（通常用于您自行读取的 MemoryStream）；此后调用方负责释放。 |

### 另见

* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
