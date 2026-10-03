---
title: "VcfLoadOptions"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "加载 Vcf 文档的选项。"
type: docs
weight: 2890
url: /zh/net/groupdocs.conversion.options.load/vcfloadoptions/
---
## VcfLoadOptions class

加载 Vcf 文档的选项。

```csharp
public sealed class VcfLoadOptions : LoadOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [VcfLoadOptions](vcfloadoptions)() | 初始化 [`VcfLoadOptions`](../vcfloadoptions) 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Encoding](../../groupdocs.conversion.options.load/vcfloadoptions/encoding) { get; set; } | 获取或设置加载 Vcf 文档时使用的编码。默认值为 Encoding.Default。 |
| [Format](../../groupdocs.conversion.options.load/vcfloadoptions/format) { get; } | 输入文档的文件类型。该值在设置格式之前为 `null`，因此应检查是否为 `null`，而不是与 [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown) 比较，因为它永不等于该值。 |
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
