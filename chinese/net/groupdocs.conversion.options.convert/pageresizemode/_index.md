---
title: "PageResizeMode"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "指定在更改页面大小时内容应如何缩放"
type: docs
weight: 2050
url: /zh/net/groupdocs.conversion.options.convert/pageresizemode/
---
## PageResizeMode class

指定在更改页面大小时内容应如何缩放

```csharp
public sealed class PageResizeMode : Enumeration
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | 将当前对象与其他对象进行比较。 |
| virtual [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(Enumeration) | 确定两个对象实例是否相等。 |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | 确定两个对象实例是否相等。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | 充当默认的哈希函数。 |
| override [ToString](../../groupdocs.conversion.contracts/enumeration/tostring)() | 返回表示当前对象的字符串。 |

## Fields

| 名称 | 描述 |
| --- | --- |
| static [AlignTopLeft](../../groupdocs.conversion.options.convert/pageresizemode/aligntopleft) | 未应用缩放。内容对齐到左上角。 |
| static [ScaleToFill](../../groupdocs.conversion.options.convert/pageresizemode/scaletofill) | 拉伸内容以填满整个页面。可能会扭曲宽高比。 |
| static [ScaleToFit](../../groupdocs.conversion.options.convert/pageresizemode/scaletofit) | 按比例缩放内容以适应整个页面且不溢出。可能会出现空白。 |
| static [ScaleToHeight](../../groupdocs.conversion.options.convert/pageresizemode/scaletoheight) | 按比例缩放内容以匹配页面高度。宽度可能溢出并被裁剪。 |
| static [ScaleToWidth](../../groupdocs.conversion.options.convert/pageresizemode/scaletowidth) | 按比例缩放内容以匹配页面宽度。高度可能会溢出并被裁剪。 |

### 另见

* class [Enumeration](../../groupdocs.conversion.contracts/enumeration)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
