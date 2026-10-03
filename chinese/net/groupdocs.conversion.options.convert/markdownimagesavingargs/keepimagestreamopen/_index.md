---
title: "KeepImageStreamOpen"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "当为 false（默认）时，转换器在写入后关闭 ImageStreamgroupdocs.conversion.options.convert/markdownimagesavingargs/imagestream —— 这对 FileStream 替代品应刷新到磁盘。设为 true 则在转换完成后保持流打开，通常用于您自行读取的 MemoryStream，调用方随后负责释放。"
type: docs
weight: 30
url: /zh/net/groupdocs.conversion.options.convert/markdownimagesavingargs/keepimagestreamopen/
---
## MarkdownImageSavingArgs.KeepImageStreamOpen property

当为 false（默认）时，转换器在写入后关闭 [`ImageStream`](../imagestream) —— 这对应于应刷新到磁盘的 FileStream 替代品。设为 true 则在转换完成后保持流打开（通常用于您自行读取的 MemoryStream）；调用方随后负责释放。

```csharp
public bool KeepImageStreamOpen { get; set; }
```

### 另见

* class [MarkdownImageSavingArgs](../../markdownimagesavingargs)
* namespace [GroupDocs.Conversion.Options.Convert](../../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
