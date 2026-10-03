---
title: "ImageConvertOptions"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "转换为 Image 文件类型的选项。"
type: docs
weight: 1950
url: /zh/net/groupdocs.conversion.options.convert/imageconvertoptions/
---
## ImageConvertOptions class

转换为 Image 文件类型的选项。

```csharp
public sealed class ImageConvertOptions : CommonConvertOptions<ImageFileType>, IUsePdfConvertOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [ImageConvertOptions](imageconvertoptions)() | 初始化 [`ImageConvertOptions`](../imageconvertoptions) 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BackgroundColor](../../groupdocs.conversion.options.convert/imageconvertoptions/backgroundcolor) { get; set; } | 在源格式支持的情况下设置背景颜色 |
| [Brightness](../../groupdocs.conversion.options.convert/imageconvertoptions/brightness) { get; set; } | 调整图像亮度。 |
| [CapResolutionToPageContent](../../groupdocs.conversion.options.convert/imageconvertoptions/capresolutiontopagecontent) { get; set; } | 设置后，将每页 PDF 的渲染分辨率限制为页面本机光栅分辨率，从而页面永远不会以高于其嵌入图像实际包含的 DPI 渲染，并在最终输出中以其本机（更小）的像素尺寸和本机 DPI 输出该页面，而不是重新放大到请求的 DPI。仅影响以图像为主（扫描）的页面；包含文本或矢量内容的页面永不被软化，并以请求的 DPI 输出。当显式设置输出 [`Width`](./width) 或 [`Height`](./height) 时跳过此限制。默认值为 `false`（不限制；每页都以请求的 DPI 渲染并输出）。 |
| [Contrast](../../groupdocs.conversion.options.convert/imageconvertoptions/contrast) { get; set; } | 调整图像对比度。 |
| [CropArea](../../groupdocs.conversion.options.convert/imageconvertoptions/croparea) { get; set; } | 转换后裁剪光栅图像区域 |
| [FlipMode](../../groupdocs.conversion.options.convert/imageconvertoptions/flipmode) { get; set; } | 图像翻转模式。 |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | 输入文档应转换成的目标文件类型。 |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | 实现 [`Format`](../iconvertoptions/format) |
| [Gamma](../../groupdocs.conversion.options.convert/imageconvertoptions/gamma) { get; set; } | 调整图像伽马。 |
| [Grayscale](../../groupdocs.conversion.options.convert/imageconvertoptions/grayscale) { get; set; } | 指示是否转换为灰度图像。 |
| [Height](../../groupdocs.conversion.options.convert/imageconvertoptions/height) { get; set; } | 转换后期望的图像高度。 |
| [HorizontalResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/horizontalresolution) { get; set; } | 转换后期望的图像水平分辨率。默认分辨率为输入文件的分辨率或 96 dpi。 |
| [JpegOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/jpegoptions) { get; set; } | Jpeg 特定的转换选项。 |
| [MinResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/minresolution) { get; set; } | 在启用 [`CapResolutionToPageContent`](./capresolutiontopagecontent) 时，对受限渲染 DPI 应用每轴的下限。受限 DPI 永不低于此值。默认值为 `0`（无下限）。 |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | 实现 [`PageNumber`](../ipagedconvertoptions/pagenumber) |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | 实现 [`Pages`](../ipagerangedconvertoptions/pages) |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | 实现 [`PagesCount`](../ipagedconvertoptions/pagescount) |
| [PsdOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/psdoptions) { get; set; } | Psd 特定的转换选项。 |
| [RotateAngle](../../groupdocs.conversion.options.convert/imageconvertoptions/rotateangle) { get; set; } | 图像旋转角度。 |
| [TiffOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/tiffoptions) { get; set; } | Tiff 特定的转换选项。 |
| [UsePdf](../../groupdocs.conversion.options.convert/imageconvertoptions/usepdf) { get; set; } | 如果 `true`，输入首先会被转换为 PDF，然后再转换为所需格式 |
| [VerticalResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/verticalresolution) { get; set; } | 转换后期望的图像垂直分辨率。默认分辨率为输入文件的分辨率或 96 dpi。 |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | 实现 [`Watermark`](../iwatermarkedconvertoptions/watermark) |
| [WebpOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/webpoptions) { get; set; } | Webp 特定的转换选项。 |
| [Width](../../groupdocs.conversion.options.convert/imageconvertoptions/width) { get; set; } | 转换后期望的图像宽度。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | 克隆当前选项实例。 |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 确定两个对象实例是否相等。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 确定两个对象实例是否相等。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | 充当默认的哈希函数。 |

### 另见

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [ImageFileType](../../groupdocs.conversion.filetypes/imagefiletype)
* interface [IUsePdfConvertOptions](../iusepdfconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
