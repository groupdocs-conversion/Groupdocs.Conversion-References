---
title: "RasterImageLoadOptions"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "加载图像文档的选项。"
type: docs
weight: 2800
url: /zh/net/groupdocs.conversion.options.load/rasterimageloadoptions/
---
## RasterImageLoadOptions class

加载图像文档的选项。

```csharp
public sealed class RasterImageLoadOptions : BaseImageLoadOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [RasterImageLoadOptions](rasterimageloadoptions)() | 初始化 [`RasterImageLoadOptions`](../rasterimageloadoptions) 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CropArea](../../groupdocs.conversion.options.load/rasterimageloadoptions/croparea) { get; set; } | 在转换前裁剪图像区域 |
| [DefaultFont](../../groupdocs.conversion.options.load/baseimageloadoptions/defaultfont) { get; set; } | Psd、Emf、Wmf 文档类型的默认字体。如果缺少字体，将使用以下字体。 |
| [Format](../../groupdocs.conversion.options.load/rasterimageloadoptions/format) { get; set; } | 输入文档的文件类型。 |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | 输入文档的文件类型。 |
| [ResetFontFolders](../../groupdocs.conversion.options.load/baseimageloadoptions/resetfontfolders) { get; set; } | 在加载文档之前重置字体文件夹。 |
| [VectorizationOptions](../../groupdocs.conversion.options.load/rasterimageloadoptions/vectorizationoptions) { get; set; } | 设置矢量化选项 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 确定两个对象实例是否相等。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 确定两个对象实例是否相等。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | 充当默认的哈希函数。 |
| [SetHeicConnector](../../groupdocs.conversion.options.load/rasterimageloadoptions/setheicconnector)(IHeicConnector) | 设置 Heic 图像连接器 |
| [SetOcrConnector](../../groupdocs.conversion.options.load/rasterimageloadoptions/setocrconnector)(IOcrConnector) | 设置图像 OCR 连接器 |

### 另见

* class [BaseImageLoadOptions](../baseimageloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
