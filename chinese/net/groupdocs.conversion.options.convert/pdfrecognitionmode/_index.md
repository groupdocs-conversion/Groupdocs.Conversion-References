---
title: "PdfRecognitionMode"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "允许控制 PDF 文档如何转换为文字处理文档。"
type: docs
weight: 2160
url: /zh/net/groupdocs.conversion.options.convert/pdfrecognitionmode/
---
## PdfRecognitionMode class

允许控制 PDF 文档如何转换为文字处理文档。

```csharp
public sealed class PdfRecognitionMode : Enumeration
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | 将当前对象与其他对象进行比较。 |
| virtual [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(Enumeration) | 确定两个对象实例是否相等。 |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | 确定两个对象实例是否相等。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | 充当默认的哈希函数。 |
| override [ToString](../../groupdocs.conversion.contracts/enumeration/tostring)() | 返回表示当前对象的字符串。 |

## Fields

| 名称 | 描述 |
| --- | --- |
| static readonly [Flow](../../groupdocs.conversion.options.convert/pdfrecognitionmode/flow) | 完整识别模式，引擎执行分组和多层分析以恢复原始文档作者的意图并生成可最大程度编辑的文档。缺点是输出文档可能与原始 PDF 文件的外观不同。 |
| static readonly [Textbox](../../groupdocs.conversion.options.convert/pdfrecognitionmode/textbox) | 此模式快速且能够最大程度保留 PDF 文件的原始外观，但生成文档的可编辑性可能受限。原始 PDF 文件中每个视觉上分组的文本块都会转换为生成文档中的文本框。这实现了输出文档与原始 PDF 文件的最大相似度。输出文档外观良好，但它完全由文本框组成，这会使在 Microsoft Word 中进一步编辑文档变得相当困难。这是默认模式。 |

### 另见

* class [Enumeration](../../groupdocs.conversion.contracts/enumeration)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
