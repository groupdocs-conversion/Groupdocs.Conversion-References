---
title: "BitmapInfo"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "包含像素数组和位图信息的对象。"
type: docs
weight: 70
url: /zh/net/groupdocs.conversion.contracts/bitmapinfo/
---
## BitmapInfo class

包含像素数组和位图信息的对象。

```csharp
public class BitmapInfo : ValueObject
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Format](../../groupdocs.conversion.contracts/bitmapinfo/format) { get; } | 获取位图的像素格式。 |
| [Height](../../groupdocs.conversion.contracts/bitmapinfo/height) { get; } | 获取位图的高度。 |
| [PixelBytes](../../groupdocs.conversion.contracts/bitmapinfo/pixelbytes) { get; } | 获取像素数组。 |
| [Width](../../groupdocs.conversion.contracts/bitmapinfo/width) { get; } | 获取位图的宽度。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [Create](../../groupdocs.conversion.contracts/bitmapinfo/create)(byte[], int, int, PixelFormat) | 创建新的 BitmapInfo 实例 |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 确定两个对象实例是否相等。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 确定两个对象实例是否相等。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | 充当默认的哈希函数。 |

## 其他成员

| 名称 | 描述 |
| --- | --- |
| class [PixelFormat](bitmapinfo.pixelformat) | 描述像素格式枚举 |

### 另见

* class [ValueObject](../valueobject)
* namespace [GroupDocs.Conversion.Contracts](../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
