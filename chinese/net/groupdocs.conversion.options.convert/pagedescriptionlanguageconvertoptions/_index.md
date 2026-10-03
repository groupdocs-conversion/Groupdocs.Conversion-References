---
title: "PageDescriptionLanguageConvertOptions"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "转换为页面描述语言文件类型的选项。"
type: docs
weight: 2030
url: /zh/net/groupdocs.conversion.options.convert/pagedescriptionlanguageconvertoptions/
---
## PageDescriptionLanguageConvertOptions class

转换为页面描述语言文件类型的选项。

```csharp
public class PageDescriptionLanguageConvertOptions : 
    CommonConvertOptions<PageDescriptionLanguageFileType>
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PageDescriptionLanguageConvertOptions](pagedescriptionlanguageconvertoptions)() | 初始化 [`PageDescriptionLanguageConvertOptions`](../pagedescriptionlanguageconvertoptions) 的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | 输入文档应转换成的目标文件类型。 |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | 实现 [`Format`](../iconvertoptions/format) |
| [Height](../../groupdocs.conversion.options.convert/pagedescriptionlanguageconvertoptions/height) { get; set; } | 转换后期望的页面高度，以每英寸 1/96 的设备无关像素为单位。将其保持为 0，以便目标自行保留其派生的页面高度。 |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | 实现 [`PageNumber`](../ipagedconvertoptions/pagenumber) |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | 实现 [`Pages`](../ipagerangedconvertoptions/pages) |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | 实现 [`PagesCount`](../ipagedconvertoptions/pagescount) |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | 实现 [`Watermark`](../iwatermarkedconvertoptions/watermark) |
| [Width](../../groupdocs.conversion.options.convert/pagedescriptionlanguageconvertoptions/width) { get; set; } | 转换后期望的页面宽度，以每英寸 1/96 的设备无关像素为单位。将其保持为 0，以便目标自行保留其派生的页面宽度。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | 克隆当前选项实例。 |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 确定两个对象实例是否相等。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 确定两个对象实例是否相等。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | 充当默认的哈希函数。 |

### 另见

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [PageDescriptionLanguageFileType](../../groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
