---
title: "SlideShow"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "仅适用于将演示文稿转换为 Htmlgroupdocs.conversion.filetypes/webfiletype/html 或 Htmgroupdocs.conversion.filetypes/webfiletype/htm，其他所有转换均会忽略此设置。指定演示文稿是否以交互式 HTML 幻灯片的形式呈现，包含幻灯片切换和形状动画，而不是默认的静态 HTML 页面。默认值为 false。"
type: docs
weight: 50
url: /zh/net/groupdocs.conversion.options.convert/webconvertoptions/slideshow/
---
## WebConvertOptions.SlideShow property

仅适用于将演示文稿转换为 [`Html`](../../../groupdocs.conversion.filetypes/webfiletype/html) 或 [`Htm`](../../../groupdocs.conversion.filetypes/webfiletype/htm)，其他所有转换均会忽略此设置。指定演示文稿是否以交互式 HTML 幻灯片的形式呈现，包含幻灯片切换和形状动画，而不是默认的静态 HTML 页面。默认值为 false。

```csharp
public bool SlideShow { get; set; }
```

### 备注

结果是一个包含内联样式、脚本、图像、字体和媒体的单个 HTML 文件。驱动幻灯片的两个 JavaScript 库从 CDN 加载，因此页面需要互联网连接才能进行动画和导航。

### 另见

* class [WebConvertOptions](../../webconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
