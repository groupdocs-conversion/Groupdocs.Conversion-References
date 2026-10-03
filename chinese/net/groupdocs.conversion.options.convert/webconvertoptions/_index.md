---
title: "WebConvertOptions"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "转换为 Web 文件类型的选项。"
type: docs
weight: 2320
url: /zh/net/groupdocs.conversion.options.convert/webconvertoptions/
---
## WebConvertOptions class

转换为 Web 文件类型的选项。

```csharp
public class WebConvertOptions : CommonConvertOptions<WebFileType>, IUsePdfConvertOptions, 
    IZoomConvertOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [WebConvertOptions](webconvertoptions)() | 初始化一个新的 [`WebConvertOptions`](../webconvertoptions) 类实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [EmbedFontResources](../../groupdocs.conversion.options.convert/webconvertoptions/embedfontresources) { get; set; } | 指定是否在主 HTML 中嵌入字体资源。默认值为 false。注意：如果 FixedLayout 设置为 true，字体资源将始终被嵌入。 |
| [FixedLayout](../../groupdocs.conversion.options.convert/webconvertoptions/fixedlayout) { get; set; } | 如果 `true` 将使用固定布局，例如绝对定位的 html 元素 默认：true |
| [FixedLayoutShowBorders](../../groupdocs.conversion.options.convert/webconvertoptions/fixedlayoutshowborders) { get; set; } | 在转换为固定布局时显示页面边框。默认是 True。 |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | 输入文档应转换成的目标文件类型。 |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | 实现 [`Format`](../iconvertoptions/format) |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | 实现 [`PageNumber`](../ipagedconvertoptions/pagenumber) |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | 实现 [`Pages`](../ipagerangedconvertoptions/pages) |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | 实现 [`PagesCount`](../ipagedconvertoptions/pagescount) |
| [SlideShow](../../groupdocs.conversion.options.convert/webconvertoptions/slideshow) { get; set; } | 仅适用于将演示文稿转换为 [`Html`](../../groupdocs.conversion.filetypes/webfiletype/html) 或 [`Htm`](../../groupdocs.conversion.filetypes/webfiletype/htm)，对其他所有转换均被忽略。指定演示文稿是否成为具有幻灯片切换和形状动画的交互式 HTML 幻灯片，而不是默认的静态 HTML 页面。默认是 false。 |
| [UsePdf](../../groupdocs.conversion.options.convert/webconvertoptions/usepdf) { get; set; } | 如果 `true`，输入首先会被转换为 PDF，然后再转换为所需格式 |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | 实现 [`Watermark`](../iwatermarkedconvertoptions/watermark) |
| [Zoom](../../groupdocs.conversion.options.convert/webconvertoptions/zoom) { get; set; } | 指定百分比的缩放级别。默认值为 100。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | 克隆当前选项实例。 |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 确定两个对象实例是否相等。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 确定两个对象实例是否相等。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | 充当默认的哈希函数。 |

### 另见

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [WebFileType](../../groupdocs.conversion.filetypes/webfiletype)
* interface [IUsePdfConvertOptions](../iusepdfconvertoptions)
* interface [IZoomConvertOptions](../izoomconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
