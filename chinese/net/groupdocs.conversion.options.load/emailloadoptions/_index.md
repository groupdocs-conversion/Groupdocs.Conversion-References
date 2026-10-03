---
title: "EmailLoadOptions"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "加载 Email 文档的选项。"
type: docs
weight: 2500
url: /zh/net/groupdocs.conversion.options.load/emailloadoptions/
---
## EmailLoadOptions class

加载 Email 文档的选项。

```csharp
public sealed class EmailLoadOptions : LoadOptions, ICustomCssStyleOptions, 
    IDocumentsContainerLoadOptions, IFontSubstituteLoadOptions, IPageLayoutOptions, 
    IPageMarginOptions, IPageOrientationOptions, IPageSizeOptions, IResourceLoadingOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmailLoadOptions](emailloadoptions)() | 初始化 [`EmailLoadOptions`](../emailloadoptions) 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AttachmentIcons](../../groupdocs.conversion.options.load/emailloadoptions/attachmenticons) { get; set; } | 获取或设置附件图标列表。该列表可以自定义，以为不同文件类型提供特定图标。默认情况下，包含常见文件类型的图标。 |
| [ConvertOwned](../../groupdocs.conversion.options.load/emailloadoptions/convertowned) { get; set; } | 实现 [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) 默认值为 true |
| [ConvertOwner](../../groupdocs.conversion.options.load/emailloadoptions/convertowner) { get; set; } | 实现 [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) 默认值为 true |
| [CustomCssStyle](../../groupdocs.conversion.options.load/emailloadoptions/customcssstyle) { get; set; } | 实现 [`CustomCssStyle`](../icustomcssstyleoptions/customcssstyle) |
| [DefaultFont](../../groupdocs.conversion.options.load/emailloadoptions/defaultfont) { get; set; } | 电子邮件文档的默认字体。如果缺少字体，将使用以下字体。 |
| [Depth](../../groupdocs.conversion.options.load/emailloadoptions/depth) { get; set; } | 实现 [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth) 默认值：1 |
| [DisplayAttachments](../../groupdocs.conversion.options.load/emailloadoptions/displayattachments) { get; set; } | 在标题中显示或隐藏附件的选项。默认值：true。 |
| [DisplayBccEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displaybccemailaddress) { get; set; } | 在标题中显示或隐藏 "Bcc" 电子邮件地址的选项。默认值：false。 |
| [DisplayCcEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displayccemailaddress) { get; set; } | 在标题中显示或隐藏 "Cc" 电子邮件地址的选项。默认值：false。 |
| [DisplayEmailAddresses](../../groupdocs.conversion.options.load/emailloadoptions/displayemailaddresses) { get; set; } | 控制是否在名称旁显示电子邮件地址的选项。例如：“John Doe &lt;john.doe@sample.com&gt;” 或仅 “John Doe”。默认值：true。 |
| [DisplayFromEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displayfromemailaddress) { get; set; } | 在标题中显示或隐藏 “from” 电子邮件地址的选项。默认值：true。 |
| [DisplayHeader](../../groupdocs.conversion.options.load/emailloadoptions/displayheader) { get; set; } | 在标题中显示或隐藏电子邮件标题的选项。默认值：true。 |
| [DisplaySent](../../groupdocs.conversion.options.load/emailloadoptions/displaysent) { get; set; } | 在标题中显示或隐藏发送日期/时间的选项。默认值：true。 |
| [DisplaySubject](../../groupdocs.conversion.options.load/emailloadoptions/displaysubject) { get; set; } | 在标题中显示或隐藏主题的选项。默认值：true。 |
| [DisplayToEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displaytoemailaddress) { get; set; } | 在标题中显示或隐藏 “to” 电子邮件地址的选项。默认值：true。 |
| [FieldTextMap](../../groupdocs.conversion.options.load/emailloadoptions/fieldtextmap) { get; set; } | 电子邮件消息 [`EmailField`](../emailfield) 与字段文本表示之间的映射 |
| [FontSubstitutes](../../groupdocs.conversion.options.load/emailloadoptions/fontsubstitutes) { get; set; } | 字体替代列表。 |
| [Format](../../groupdocs.conversion.options.load/emailloadoptions/format) { get; set; } | 输入文档的文件类型。该值在设置格式之前为 `null`，因此应检查是否为 `null`，而不是与 [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown) 比较，因为它永不等于该值。 |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | 输入文档的文件类型。 |
| [MarginSettings](../../groupdocs.conversion.options.load/emailloadoptions/marginsettings) { get; set; } | 页面边距设置 |
| [OrientationSettings](../../groupdocs.conversion.options.load/emailloadoptions/orientationsettings) { get; set; } | 页面方向设置 |
| [PageLayoutOptions](../../groupdocs.conversion.options.load/emailloadoptions/pagelayoutoptions) { get; set; } | 实现 [`PageLayoutOptions`](../ipagelayoutoptions/pagelayoutoptions) |
| [PreserveOriginalDate](../../groupdocs.conversion.options.load/emailloadoptions/preserveoriginaldate) { get; set; } | 定义在保存邮件时是否需要保留原始日期标题字符串（默认值为 true） |
| [ResourceLoadingTimeout](../../groupdocs.conversion.options.load/emailloadoptions/resourceloadingtimeout) { get; set; } | 加载外部资源的超时时间 |
| [SizeSettings](../../groupdocs.conversion.options.load/emailloadoptions/sizesettings) { get; set; } | 页面尺寸设置 |
| [SkipExternalResources](../../groupdocs.conversion.options.load/emailloadoptions/skipexternalresources) { get; set; } | 实现 [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [TimeZoneOffset](../../groupdocs.conversion.options.load/emailloadoptions/timezoneoffset) { get; set; } | 获取或设置消息日期的协调世界时 (UTC) 偏移量。此属性定义本地时间与 UTC 之间的时区差异。 |
| [UseDefaultAttachmentIcons](../../groupdocs.conversion.options.load/emailloadoptions/usedefaultattachmenticons) { get; set; } | 获取或设置是否使用默认附件图标。默认值：true。 |
| [WhitelistedResources](../../groupdocs.conversion.options.load/emailloadoptions/whitelistedresources) { get; set; } | 实现 [`WhitelistedResources`](../iresourceloadingoptions/whitelistedresources) |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.load/emailloadoptions/clone)() | 克隆当前实例。 |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 确定两个对象实例是否相等。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 确定两个对象实例是否相等。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | 充当默认的哈希函数。 |

### 另见

* class [LoadOptions](../loadoptions)
* interface [ICustomCssStyleOptions](../icustomcssstyleoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* interface [IFontSubstituteLoadOptions](../ifontsubstituteloadoptions)
* interface [IPageLayoutOptions](../ipagelayoutoptions)
* interface [IPageMarginOptions](../../groupdocs.conversion.options/ipagemarginoptions)
* interface [IPageOrientationOptions](../../groupdocs.conversion.options/ipageorientationoptions)
* interface [IPageSizeOptions](../../groupdocs.conversion.options/ipagesizeoptions)
* interface [IResourceLoadingOptions](../iresourceloadingoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
