---
title: "WebLoadOptions"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "加载网页文档的选项。"
type: docs
weight: 2920
url: /zh/net/groupdocs.conversion.options.load/webloadoptions/
---
## WebLoadOptions class

加载网页文档的选项。

```csharp
public class WebLoadOptions : LoadOptions, ICustomCssStyleOptions, IPageLayoutOptions, 
    IPageMarginOptions, IPageNumberingLoadOptions, IPageOrientationOptions, IPageSizeOptions, 
    IResourceLoadingOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [WebLoadOptions](webloadoptions)() | 初始化 [`WebLoadOptions`](../webloadoptions) 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BasePath](../../groupdocs.conversion.options.load/webloadoptions/basepath) { get; set; } | HTML 的基础路径/URL |
| [ConfigureHeaders](../../groupdocs.conversion.options.load/webloadoptions/configureheaders) { get; set; } | 用于配置请求头的操作。该操作的第一个参数是 Uri。 |
| [CredentialsProvider](../../groupdocs.conversion.options.load/webloadoptions/credentialsprovider) { get; set; } | Uri 的凭据提供程序。 |
| [CustomCssStyle](../../groupdocs.conversion.options.load/webloadoptions/customcssstyle) { get; set; } | 实现 [`CustomCssStyle`](../icustomcssstyleoptions/customcssstyle) |
| [Encoding](../../groupdocs.conversion.options.load/webloadoptions/encoding) { get; set; } | 获取或设置加载网页文档时使用的编码。如果属性为 null，将根据文档字符集属性确定编码。 |
| [Format](../../groupdocs.conversion.options.load/webloadoptions/format) { get; set; } | 输入文档的文件类型。该值在设置格式之前为 `null`，因此应检查是否为 `null`，而不是与 [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown) 比较，因为它永不等于该值。 |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | 输入文档的文件类型。 |
| [HtmlRenderingMode](../../groupdocs.conversion.options.load/webloadoptions/htmlrenderingmode) { get; set; } | 控制 HTML 内容的渲染方式。默认：AbsolutePositioning |
| [MarginSettings](../../groupdocs.conversion.options.load/webloadoptions/marginsettings) { get; set; } | 页面边距设置 |
| [OrientationSettings](../../groupdocs.conversion.options.load/webloadoptions/orientationsettings) { get; set; } | 页面方向设置 |
| [PageLayoutOptions](../../groupdocs.conversion.options.load/webloadoptions/pagelayoutoptions) { get; set; } | 指定加载网页文档时的页面布局选项。 |
| [PageNumbering](../../groupdocs.conversion.options.load/webloadoptions/pagenumbering) { get; set; } | 启用或禁用在转换后文档中生成页码。默认值：false |
| [ResourceLoadingTimeout](../../groupdocs.conversion.options.load/webloadoptions/resourceloadingtimeout) { get; set; } | 加载外部资源的超时时间 |
| [SizeSettings](../../groupdocs.conversion.options.load/webloadoptions/sizesettings) { get; set; } | 页面尺寸设置 |
| [SkipExternalResources](../../groupdocs.conversion.options.load/webloadoptions/skipexternalresources) { get; set; } | 实现 [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [UsePdf](../../groupdocs.conversion.options.load/webloadoptions/usepdf) { get; set; } | 使用 pdf 进行转换。默认值：false |
| [WhitelistedResources](../../groupdocs.conversion.options.load/webloadoptions/whitelistedresources) { get; set; } | 实现 [`WhitelistedResources`](../iresourceloadingoptions/whitelistedresources) |
| [Zoom](../../groupdocs.conversion.options.load/webloadoptions/zoom) { get; set; } | 指定缩放级别（百分比）。缩放级别在转换前应用于文档的 &lt;body&gt; 标记，以缩放文档的视觉外观。100% 表示原始大小。默认值为 100。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 确定两个对象实例是否相等。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 确定两个对象实例是否相等。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | 充当默认的哈希函数。 |

### 另见

* class [LoadOptions](../loadoptions)
* interface [ICustomCssStyleOptions](../icustomcssstyleoptions)
* interface [IPageLayoutOptions](../ipagelayoutoptions)
* interface [IPageMarginOptions](../../groupdocs.conversion.options/ipagemarginoptions)
* interface [IPageNumberingLoadOptions](../ipagenumberingloadoptions)
* interface [IPageOrientationOptions](../../groupdocs.conversion.options/ipageorientationoptions)
* interface [IPageSizeOptions](../../groupdocs.conversion.options/ipagesizeoptions)
* interface [IResourceLoadingOptions](../iresourceloadingoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
