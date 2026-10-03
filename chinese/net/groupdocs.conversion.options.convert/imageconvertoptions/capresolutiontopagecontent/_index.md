---
title: "CapResolutionToPageContent"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "设置后，将每页 PDF 的渲染分辨率限制为页面本机光栅分辨率，从而页面永不以高于其嵌入图像实际包含的 DPI 渲染，并在最终输出中以其本机较小的像素尺寸和本机 DPI 输出该页面，而不是重新放大到请求的 DPI。仅受图像主导的扫描页受影响，包含文本或矢量内容的页面永不被软化，且以请求的 DPI 输出。当显式设置输出 Widthgroupdocs.conversion.options.convert/imageconvertoptions/width 或 Heightgroupdocs.conversion.options.convert/imageconvertoptions/height 时跳过。默认值为 false，不进行限制，每页均以请求的 DPI 渲染并输出。"
type: docs
weight: 40
url: /zh/net/groupdocs.conversion.options.convert/imageconvertoptions/capresolutiontopagecontent/
---
## ImageConvertOptions.CapResolutionToPageContent property

设置后，将每页 PDF 的渲染分辨率限制为页面本机光栅分辨率，使页面永不以高于其嵌入图像实际包含的 DPI 渲染，并在最终输出中以其本机（更小）的像素尺寸和本机 DPI 输出该页面，而不是重新放大到请求的 DPI。仅受图像主导（扫描）页面影响；包含文本或矢量内容的页面永不被软化，并以请求的 DPI 输出。当显式设置输出 [`Width`](../width) 或 [`Height`](../height) 时跳过。默认值为 `false`（不限制；每页均以请求的 DPI 渲染并输出）。

```csharp
public bool CapResolutionToPageContent { get; set; }
```

### 另见

* class [ImageConvertOptions](../../imageconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
