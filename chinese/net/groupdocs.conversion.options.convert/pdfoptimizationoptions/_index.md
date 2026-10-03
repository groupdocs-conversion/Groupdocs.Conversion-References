---
title: "PdfOptimizationOptions"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "定义 Pdf 优化选项。"
type: docs
weight: 2120
url: /zh/net/groupdocs.conversion.options.convert/pdfoptimizationoptions/
---
## PdfOptimizationOptions class

定义 Pdf 优化选项。

```csharp
public sealed class PdfOptimizationOptions : ValueObject
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PdfOptimizationOptions](pdfoptimizationoptions)() | 初始化 [`PdfOptimizationOptions`](../pdfoptimizationoptions) 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CompressImages](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/compressimages) { get; set; } | 如果将 CompressImages 设置为 `true`，文档中的所有图像将重新压缩。压缩方式由 ImageQuality 属性定义。 |
| [FontSubsetStrategy](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/fontsubsetstrategy) { get; set; } | 设置字体子集策略 |
| [ImageQuality](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/imagequality) { get; set; } | 以百分比表示的值，100% 表示质量和图像大小保持不变。要减小图像大小，请将此属性设置为小于 100。 |
| [LinkDuplicateStreams](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/linkduplicatestreams) { get; set; } | 链接重复流 |
| [RemoveUnusedObjects](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/removeunusedobjects) { get; set; } | 移除未使用的对象 |
| [RemoveUnusedStreams](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/removeunusedstreams) { get; set; } | 移除未使用的流 |
| [UnembedFonts](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/unembedfonts) { get; set; } | 如果设置为 true，则不嵌入字体 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 确定两个对象实例是否相等。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 确定两个对象实例是否相等。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | 充当默认的哈希函数。 |

### 另见

* class [ValueObject](../../groupdocs.conversion.contracts/valueobject)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
