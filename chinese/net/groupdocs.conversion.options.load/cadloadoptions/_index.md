---
title: "CadLoadOptions"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "加载 CAD 文档的选项。"
type: docs
weight: 2430
url: /zh/net/groupdocs.conversion.options.load/cadloadoptions/
---
## CadLoadOptions class

加载 CAD 文档的选项。

```csharp
public sealed class CadLoadOptions : LoadOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [CadLoadOptions](cadloadoptions)() | 初始化 [`CadLoadOptions`](../cadloadoptions) 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BackgroundColor](../../groupdocs.conversion.options.load/cadloadoptions/backgroundcolor) { get; set; } | 获取或设置背景颜色。 |
| [CtbSources](../../groupdocs.conversion.options.load/cadloadoptions/ctbsources) { get; set; } | 获取或设置 CTB 源。 |
| [DrawColor](../../groupdocs.conversion.options.load/cadloadoptions/drawcolor) { get; set; } | 获取或设置前景颜色。 |
| [DrawType](../../groupdocs.conversion.options.load/cadloadoptions/drawtype) { get; set; } | 获取或设置绘图的类型。 |
| [Format](../../groupdocs.conversion.options.load/cadloadoptions/format) { get; set; } | 输入文档的文件类型。该值在设置格式之前为 `null`，因此应检查是否为 `null`，而不是与 [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown) 比较，因为它永不等于该值。 |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | 输入文档的文件类型。 |
| [LayoutNames](../../groupdocs.conversion.options.load/cadloadoptions/layoutnames) { get; set; } | 指定要转换的 CAD 布局。 |
| [LayoutScope](../../groupdocs.conversion.options.load/cadloadoptions/layoutscope) { get; set; } | 获取或设置要转换的绘图空间。默认值为 [`Both`](../cadlayoutscope/both)，该值不限制转换。当提供了 [`LayoutNames`](./layoutnames) 时会被忽略，因为显式的布局名称始终优先。`null` 值将被视为 [`Both`](../cadlayoutscope/both)。 |

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
