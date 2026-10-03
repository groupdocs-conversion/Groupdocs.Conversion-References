---
title: "PageLayoutOptions"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "描述加载网页文档时的页面布局模式。"
type: docs
weight: 2720
url: /zh/net/groupdocs.conversion.options.load/pagelayoutoptions/
---
## PageLayoutOptions class

描述加载网页文档时的页面布局模式。

```csharp
public class PageLayoutOptions : FlagsEnumeration
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | 将当前对象与其他对象进行比较。 |
| virtual [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(Enumeration) | 确定两个对象实例是否相等。 |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | 确定两个对象实例是否相等。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | 充当默认的哈希函数。 |
| virtual [HasFlag&lt;T&gt;](../../groupdocs.conversion.contracts/flagsenumeration/hasflag)(T) | 检查当前标志是否具有指定的标志。 |
| virtual [HasFlagValue](../../groupdocs.conversion.contracts/flagsenumeration/hasflagvalue)(int) | 检查当前标志是否具有指定的值。 |
| override [ToString](../../groupdocs.conversion.contracts/flagsenumeration/tostring)() | 将当前对象转换为字符串。 |
| [operator &#x7C;](../../groupdocs.conversion.options.load/pagelayoutoptions/op_bitwiseor) | 使用按位或将两个 [`PageLayoutOptions`](../pagelayoutoptions) 标志组合在一起。 |

## Fields

| 名称 | 描述 |
| --- | --- |
| static readonly [None](../../groupdocs.conversion.options.load/pagelayoutoptions/none) | 默认值 |
| static readonly [ScaleToPageHeight](../../groupdocs.conversion.options.load/pagelayoutoptions/scaletopageheight) | 此标志表示文档内容将被缩放以适应首页的高度。所有文档内容将仅放置在单页上。 |
| static readonly [ScaleToPageWidth](../../groupdocs.conversion.options.load/pagelayoutoptions/scaletopagewidth) | 指示文档内容将按比例缩放以适应页面，选择可用页面宽度与重叠内容差异最大的位置。 |

### 另见

* class [FlagsEnumeration](../../groupdocs.conversion.contracts/flagsenumeration)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
