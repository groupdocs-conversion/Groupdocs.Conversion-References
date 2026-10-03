---
title: "VectorizationOptions"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "矢量化图像的选项。"
type: docs
weight: 2900
url: /zh/net/groupdocs.conversion.options.load/vectorizationoptions/
---
## VectorizationOptions class

矢量化图像的选项。

```csharp
public class VectorizationOptions : ValueObject
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [VectorizationOptions](vectorizationoptions)() | VectorizationOptions 的默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BackgroundColor](../../groupdocs.conversion.options.load/vectorizationoptions/backgroundcolor) { get; set; } | 获取或设置背景颜色。默认值为透明白色。 |
| [ColorsLimit](../../groupdocs.conversion.options.load/vectorizationoptions/colorslimit) { get; set; } | 获取或设置用于量化图像的最大颜色数。默认值为 25。 |
| [EnableVectorization](../../groupdocs.conversion.options.load/vectorizationoptions/enablevectorization) { get; set; } | 启用图像矢量化。默认值为 false。 |
| [ImageSizeLimit](../../groupdocs.conversion.options.load/vectorizationoptions/imagesizelimit) { get; set; } | 获取或设置通过图像宽度与高度相乘确定的图像最大尺寸。图像的大小将根据此属性进行缩放。默认值为 1800000。 |
| [LineWidth](../../groupdocs.conversion.options.load/vectorizationoptions/linewidth) { get; set; } | 获取或设置线宽。此参数的值受图形比例影响。默认值为 1。 |
| [Severity](../../groupdocs.conversion.options.load/vectorizationoptions/severity) { get; set; } | 设置图像追踪平滑程度 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 确定两个对象实例是否相等。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 确定两个对象实例是否相等。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | 充当默认的哈希函数。 |

### 另见

* class [ValueObject](../../groupdocs.conversion.contracts/valueobject)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
