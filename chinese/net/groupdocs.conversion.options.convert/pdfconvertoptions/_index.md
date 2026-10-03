---
title: "PdfConvertOptions"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "转换为 Pdf 文件类型的选项。"
type: docs
weight: 2060
url: /zh/net/groupdocs.conversion.options.convert/pdfconvertoptions/
---
## PdfConvertOptions class

转换为 Pdf 文件类型的选项。

```csharp
public class PdfConvertOptions : CommonConvertOptions<PdfFileType>, IDpiConvertOptions, 
    IPageMarginOptions, IPageOrientationOptions, IPageSizeOptions, IPasswordConvertOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PdfConvertOptions](pdfconvertoptions)() | 初始化一个新的 [`PdfConvertOptions`](../pdfconvertoptions) 类实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Dpi](../../groupdocs.conversion.options.convert/pdfconvertoptions/dpi) { get; set; } | 转换后所需的页面 DPI。默认分辨率为：96 dpi。 |
| [EmbedFullFonts](../../groupdocs.conversion.options.convert/pdfconvertoptions/embedfullfonts) { get; set; } | 设置为 true 时，完整的字体文件会嵌入 PDF，而不是子集。这会增加输出文件大小，但在编辑生成的 PDF 时可确保更好的兼容性。仅在从 WordProcessing 文档转换时适用。 |
| [FallbackPageSize](../../groupdocs.conversion.options.convert/pdfconvertoptions/fallbackpagesize) { get; set; } | 备用页面尺寸 |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | 输入文档应转换成的目标文件类型。 |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | 实现 [`Format`](../iconvertoptions/format) |
| [MarginSettings](../../groupdocs.conversion.options.convert/pdfconvertoptions/marginsettings) { get; set; } | 页面边距设置 |
| [OrientationSettings](../../groupdocs.conversion.options.convert/pdfconvertoptions/orientationsettings) { get; set; } | 页面方向设置 |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | 实现 [`PageNumber`](../ipagedconvertoptions/pagenumber) |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | 实现 [`Pages`](../ipagerangedconvertoptions/pages) |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | 实现 [`PagesCount`](../ipagedconvertoptions/pagescount) |
| [Password](../../groupdocs.conversion.options.convert/pdfconvertoptions/password) { get; set; } | 如果您想使用密码保护转换后的文档，请设置此属性。 |
| [PdfOptions](../../groupdocs.conversion.options.convert/pdfconvertoptions/pdfoptions) { get; set; } | PDF 特定的转换选项 |
| [ResizeMode](../../groupdocs.conversion.options.convert/pdfconvertoptions/resizemode) { get; set; } | 指定在更改页面尺寸时内容应如何缩放。默认是 AlignTopLeft（不缩放）。 |
| [Rotate](../../groupdocs.conversion.options.convert/pdfconvertoptions/rotate) { get; set; } | 页面旋转 |
| [SizeSettings](../../groupdocs.conversion.options.convert/pdfconvertoptions/sizesettings) { get; set; } | 页面尺寸设置 |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | 实现 [`Watermark`](../iwatermarkedconvertoptions/watermark) |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | 克隆当前选项实例。 |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 确定两个对象实例是否相等。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 确定两个对象实例是否相等。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | 充当默认的哈希函数。 |

### 另见

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [PdfFileType](../../groupdocs.conversion.filetypes/pdffiletype)
* interface [IDpiConvertOptions](../idpiconvertoptions)
* interface [IPageMarginOptions](../../groupdocs.conversion.options/ipagemarginoptions)
* interface [IPageOrientationOptions](../../groupdocs.conversion.options/ipageorientationoptions)
* interface [IPageSizeOptions](../../groupdocs.conversion.options/ipagesizeoptions)
* interface [IPasswordConvertOptions](../ipasswordconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
