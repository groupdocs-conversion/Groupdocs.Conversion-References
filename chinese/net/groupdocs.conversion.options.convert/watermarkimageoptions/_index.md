---
title: "WatermarkImageOptions"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "对已转换文档设置水印的选项"
type: docs
weight: 2290
url: /zh/net/groupdocs.conversion.options.convert/watermarkimageoptions/
---
## WatermarkImageOptions class

对已转换文档设置水印的选项

```csharp
public sealed class WatermarkImageOptions : WatermarkOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [WatermarkImageOptions](watermarkimageoptions)(byte[]) | 创建 WatermarkOptions 类并设置水印文本 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AutoAlign](../../groupdocs.conversion.options.convert/watermarkoptions/autoalign) { get; set; } | 自动缩放水印。如果该值为 true，则位置和大小会自动计算以适应页面尺寸。 |
| [Background](../../groupdocs.conversion.options.convert/watermarkoptions/background) { get; set; } | 指示水印被标记为背景。如果该值为 true，水印放置在底部。默认情况下为 false，水印放置在顶部。 |
| [Height](../../groupdocs.conversion.options.convert/watermarkoptions/height) { get; set; } | 水印高度 |
| [Image](../../groupdocs.conversion.options.convert/watermarkimageoptions/image) { get; } | 图像水印 |
| [Left](../../groupdocs.conversion.options.convert/watermarkoptions/left) { get; set; } | 水印左侧位置 |
| [RotationAngle](../../groupdocs.conversion.options.convert/watermarkoptions/rotationangle) { get; set; } | 水印旋转角度 |
| [Top](../../groupdocs.conversion.options.convert/watermarkoptions/top) { get; set; } | 水印顶部位置 |
| [Transparency](../../groupdocs.conversion.options.convert/watermarkoptions/transparency) { get; set; } | 水印透明度。值在 0 到 1 之间。值 0 表示完全可见，值 1 表示不可见。 |
| [Width](../../groupdocs.conversion.options.convert/watermarkoptions/width) { get; set; } | 水印宽度 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/watermarkoptions/clone)() | 克隆当前实例 |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 确定两个对象实例是否相等。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 确定两个对象实例是否相等。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | 充当默认的哈希函数。 |

### 另见

* class [WatermarkOptions](../watermarkoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
