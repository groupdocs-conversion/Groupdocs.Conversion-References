---
title: WatermarkImageOptions
second_title: GroupDocs.Conversion for .NET API 参考
description: 为转换后的文档设置水印的选项
type: docs
weight: 1950
url: /zh/net/groupdocs.conversion.options.convert/watermarkimageoptions/
---
## WatermarkImageOptions class

为转换后的文档设置水印的选项

```csharp
public sealed class WatermarkImageOptions : WatermarkOptions
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [WatermarkImageOptions](watermarkimageoptions)(byte[]) | 创建 WatermarkOptions 类并设置水印文本 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AutoAlign](../../groupdocs.conversion.options.convert/watermarkoptions/autoalign) { get; set; } | 自动缩放水印。如果该值为真，则会自动计算位置和大小以适合页面大小。 |
| [Background](../../groupdocs.conversion.options.convert/watermarkoptions/background) { get; set; } | 表示水印被标记为背景。如果该值为 true，则水印位于底部。默认为false，水印放在最上面。 |
| [Height](../../groupdocs.conversion.options.convert/watermarkoptions/height) { get; set; } | 水印高度 |
| [Image](../../groupdocs.conversion.options.convert/watermarkimageoptions/image) { get; } | 图片水印 |
| [Left](../../groupdocs.conversion.options.convert/watermarkoptions/left) { get; set; } | 水印左位置 |
| [RotationAngle](../../groupdocs.conversion.options.convert/watermarkoptions/rotationangle) { get; set; } | 水印旋转角度 |
| [Top](../../groupdocs.conversion.options.convert/watermarkoptions/top) { get; set; } | 水印顶部位置 |
| [Transparency](../../groupdocs.conversion.options.convert/watermarkoptions/transparency) { get; set; } | 水印透明度。介于0和1之间的值。值0完全可见，值1不可见。 |
| [Width](../../groupdocs.conversion.options.convert/watermarkoptions/width) { get; set; } | 水印宽度 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/watermarkoptions/clone)() | 克隆当前实例 |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 判断两个对象实例是否相等。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 判断两个对象实例是否相等。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | 作为默认哈希函数。 |

### 也可以看看

* class [WatermarkOptions](../watermarkoptions)
* 命名空间 [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* 部件 [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
