---
title: "Rectangle"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "表示一个由其边缘定义的矩形，用于裁剪目的。"
type: docs
weight: 580
url: /zh/net/groupdocs.conversion.contracts/rectangle/
---
## Rectangle class

表示一个由其边缘定义的矩形，用于裁剪目的。

```csharp
public sealed class Rectangle : ValueObject
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Rectangle](rectangle)(int, int, int, int) | 使用指定的边初始化一个新的 [`Rectangle`](../rectangle) 结构体实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Bottom](../../groupdocs.conversion.contracts/rectangle/bottom) { get; } | 获取矩形的底部边缘。 |
| [Height](../../groupdocs.conversion.contracts/rectangle/height) { get; } | 根据顶部和底部边缘获取矩形的高度。 |
| [Left](../../groupdocs.conversion.contracts/rectangle/left) { get; } | 获取矩形的左侧边缘。 |
| [Right](../../groupdocs.conversion.contracts/rectangle/right) { get; } | 获取矩形的右侧边缘。 |
| [Top](../../groupdocs.conversion.contracts/rectangle/top) { get; } | 获取矩形的上边缘。 |
| [Width](../../groupdocs.conversion.contracts/rectangle/width) { get; } | 根据左侧和右侧边缘获取矩形的宽度。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Crop](../../groupdocs.conversion.contracts/rectangle/crop)(int, int, int, int) | 通过移除指定的边距创建当前矩形的裁剪版本。 |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 确定两个对象实例是否相等。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 确定两个对象实例是否相等。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | 充当默认的哈希函数。 |
| override [ToString](../../groupdocs.conversion.contracts/rectangle/tostring)() | 返回矩形的字符串表示形式。 |

### 另见

* class [ValueObject](../valueobject)
* namespace [GroupDocs.Conversion.Contracts](../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
