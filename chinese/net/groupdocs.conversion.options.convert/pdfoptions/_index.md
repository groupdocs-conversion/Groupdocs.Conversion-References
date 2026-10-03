---
title: "PdfOptions"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "转换为 Pdf 文件类型的选项。"
type: docs
weight: 2130
url: /zh/net/groupdocs.conversion.options.convert/pdfoptions/
---
## PdfOptions class

转换为 Pdf 文件类型的选项。

```csharp
public sealed class PdfOptions : ValueObject, IZoomConvertOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PdfOptions](pdfoptions)() | 初始化一个新的 [`PdfOptions`](../pdfoptions) 类实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [DocumentInfo](../../groupdocs.conversion.options.convert/pdfoptions/documentinfo) { get; set; } | PDF 文档的元信息。 |
| [FormattingOptions](../../groupdocs.conversion.options.convert/pdfoptions/formattingoptions) { get; set; } | PDF 格式化选项 |
| [Grayscale](../../groupdocs.conversion.options.convert/pdfoptions/grayscale) { get; set; } | 将 PDF 从 RGB 色彩空间转换为灰度 |
| [Linearize](../../groupdocs.conversion.options.convert/pdfoptions/linearize) { get; set; } | 为 Web 线性化 PDF 文档 |
| [OptimizationOptions](../../groupdocs.conversion.options.convert/pdfoptions/optimizationoptions) { get; set; } | PDF 优化选项 |
| [PdfFormat](../../groupdocs.conversion.options.convert/pdfoptions/pdfformat) { get; set; } | 设置转换后文档的 PDF 格式。 |
| [RemovePdfACompliance](../../groupdocs.conversion.options.convert/pdfoptions/removepdfacompliance) { get; set; } | 移除 PDF/A 合规性 |
| [Zoom](../../groupdocs.conversion.options.convert/pdfoptions/zoom) { get; set; } | 指定百分比的缩放级别。默认值为 100。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 确定两个对象实例是否相等。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 确定两个对象实例是否相等。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | 充当默认的哈希函数。 |

### 另见

* class [ValueObject](../../groupdocs.conversion.contracts/valueobject)
* interface [IZoomConvertOptions](../izoomconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
