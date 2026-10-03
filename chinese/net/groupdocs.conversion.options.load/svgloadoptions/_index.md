---
title: "SvgLoadOptions"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "加载 Svg 文档的选项。"
type: docs
weight: 2830
url: /zh/net/groupdocs.conversion.options.load/svgloadoptions/
---
## SvgLoadOptions class

加载 Svg 文档的选项。

```csharp
public class SvgLoadOptions : LoadOptions, IResourceLoadingOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [SvgLoadOptions](svgloadoptions)() | 初始化 [`SvgLoadOptions`](../svgloadoptions) 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CropToContentBounds](../../groupdocs.conversion.options.load/svgloadoptions/croptocontentbounds) { get; set; } | 获取或设置一个值，指示在转换之前是否将 SVG 边界框裁剪到内容范围。默认值为 false。 |
| [Format](../../groupdocs.conversion.options.load/svgloadoptions/format) { get; set; } | 输入文档的文件类型。该值在设置格式之前为 `null`，因此应检查是否为 `null`，而不是与 [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown) 比较，因为它永不等于该值。 |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | 输入文档的文件类型。 |
| [MinimumHeight](../../groupdocs.conversion.options.load/svgloadoptions/minimumheight) { get; set; } | 设置转换 SVG 文档的最小高度。该设置在转换为栅格格式时使用。默认值为 600。 |
| [MinimumWidth](../../groupdocs.conversion.options.load/svgloadoptions/minimumwidth) { get; set; } | 设置转换 SVG 文档的最小宽度。该设置在转换为栅格格式时使用。默认值为 800。 |
| [SkipExternalResources](../../groupdocs.conversion.options.load/svgloadoptions/skipexternalresources) { get; set; } | 实现 [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [WhitelistedResources](../../groupdocs.conversion.options.load/svgloadoptions/whitelistedresources) { get; set; } | 始终加载的外部资源。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 确定两个对象实例是否相等。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 确定两个对象实例是否相等。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | 充当默认的哈希函数。 |

### 另见

* class [LoadOptions](../loadoptions)
* interface [IResourceLoadingOptions](../iresourceloadingoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
