---
title: "HyphenationOptions"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "设置连字符文档的选项。"
type: docs
weight: 2570
url: /zh/net/groupdocs.conversion.options.load/hyphenationoptions/
---
## HyphenationOptions class

设置连字符文档的选项。

```csharp
public sealed class HyphenationOptions : ValueObject
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [HyphenationOptions](hyphenationoptions)() | 创建 [`HyphenationOptions`](../hyphenationoptions) 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AutoHyphenation](../../groupdocs.conversion.options.load/hyphenationoptions/autohyphenation) { get; set; } | 获取或设置决定文档是否启用自动连字的值。此属性的默认值为 false。 |
| [HyphenateCaps](../../groupdocs.conversion.options.load/hyphenationoptions/hyphenatecaps) { get; set; } | 获取或设置决定全大写单词是否进行连字的值。此属性的默认值为 true。 |
| [HyphenationDictionaries](../../groupdocs.conversion.options.load/hyphenationoptions/hyphenationdictionaries) { get; set; } | 字典，包含 ISO 语言代码与提供的连字字典流之间的关联。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 确定两个对象实例是否相等。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 确定两个对象实例是否相等。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | 充当默认的哈希函数。 |

### 另见

* class [ValueObject](../../groupdocs.conversion.contracts/valueobject)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
