---
title: "DiagramLoadOptions"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "加载 Diagram 文档的选项。"
type: docs
weight: 2470
url: /zh/net/groupdocs.conversion.options.load/diagramloadoptions/
---
## DiagramLoadOptions class

加载 Diagram 文档的选项。

```csharp
public sealed class DiagramLoadOptions : LoadOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [DiagramLoadOptions](diagramloadoptions)() | 初始化 [`DiagramLoadOptions`](../diagramloadoptions) 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [DefaultFont](../../groupdocs.conversion.options.load/diagramloadoptions/defaultfont) { get; set; } | Diagram 文档的默认字体。如果缺少字体，将使用以下字体。 |
| [Format](../../groupdocs.conversion.options.load/diagramloadoptions/format) { get; set; } | 输入文档的文件类型。该值在设置格式之前为 `null`，因此应检查是否为 `null`，而不是与 [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown) 比较，因为它永不等于该值。 |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | 输入文档的文件类型。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 确定两个对象实例是否相等。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 确定两个对象实例是否相等。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | 充当默认的哈希函数。 |

### 另见

* class [LoadOptions](../loadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
