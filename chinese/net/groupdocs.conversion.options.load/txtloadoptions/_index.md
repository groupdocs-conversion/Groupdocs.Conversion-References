---
title: "TxtLoadOptions"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "加载 Txt 文档的选项。"
type: docs
weight: 2870
url: /zh/net/groupdocs.conversion.options.load/txtloadoptions/
---
## TxtLoadOptions class

加载 Txt 文档的选项。

```csharp
public sealed class TxtLoadOptions : LoadOptions, IPageMarginOptions, IPageSizeOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [TxtLoadOptions](txtloadoptions)() | 初始化 [`TxtLoadOptions`](../txtloadoptions) 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [DefaultFont](../../groupdocs.conversion.options.load/txtloadoptions/defaultfont) { get; set; } | 在转换期间渲染纯文本内容时使用的字体。由于 TXT 文件不包含字体信息，此属性指定文本内容的显示字体。默认：Arial 10pt。 |
| [DetectNumberingWithWhitespaces](../../groupdocs.conversion.options.load/txtloadoptions/detectnumberingwithwhitespaces) { get; set; } | 允许指定在转换纯文本文档时如何识别编号列表项。默认值为 true。 |
| [Encoding](../../groupdocs.conversion.options.load/txtloadoptions/encoding) { get; set; } | 获取或设置加载 Txt 文档时使用的编码。可以为 null。默认值为 null。 |
| [Format](../../groupdocs.conversion.options.load/txtloadoptions/format) { get; } | 输入文档的文件类型。该值在设置格式之前为 `null`，因此应检查是否为 `null`，而不是与 [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown) 比较，因为它永不等于该值。 |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | 输入文档的文件类型。 |
| [LeadingSpacesOptions](../../groupdocs.conversion.options.load/txtloadoptions/leadingspacesoptions) { get; set; } | 获取或设置前导空格处理的首选选项。默认值为 [`ConvertToIndent`](../txtleadingspacesoptions/converttoindent)。 |
| [MarginSettings](../../groupdocs.conversion.options.load/txtloadoptions/marginsettings) { get; set; } | 页面边距设置 |
| [SizeSettings](../../groupdocs.conversion.options.load/txtloadoptions/sizesettings) { get; set; } | 页面尺寸设置 |
| [TrailingSpacesOptions](../../groupdocs.conversion.options.load/txtloadoptions/trailingspacesoptions) { get; set; } | 获取或设置尾随空格处理的首选选项。默认值为 [`Trim`](../txttrailingspacesoptions/trim)。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 确定两个对象实例是否相等。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 确定两个对象实例是否相等。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | 充当默认的哈希函数。 |

### 备注

**Font Configuration for Plain Text:**

由于 TXT 文件不包含字体信息，请使用 DefaultTextFont 指定

在转换期间渲染纯文本内容的字体。

### 另见

* class [LoadOptions](../loadoptions)
* interface [IPageMarginOptions](../../groupdocs.conversion.options/ipagemarginoptions)
* interface [IPageSizeOptions](../../groupdocs.conversion.options/ipagesizeoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
