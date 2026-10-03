---
title: "CadLayoutScope"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "表示 CAD 转换选择的绘图空间：模型空间、纸张空间布局或两者。"
type: docs
weight: 2420
url: /zh/net/groupdocs.conversion.options.load/cadlayoutscope/
---
## CadLayoutScope class

表示 CAD 转换选择的绘图空间：模型空间、纸张布局空间或两者。

```csharp
public class CadLayoutScope : Enumeration
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
| static readonly [Both](../../groupdocs.conversion.options.load/cadlayoutscope/both) | 选择模型空间和所有纸张空间布局。这是默认值，且不限制转换：当未指定范围时，绘图将完全按原样渲染。 |
| static readonly [Layouts](../../groupdocs.conversion.options.load/cadlayoutscope/layouts) | 仅选择纸张空间布局。模型空间被排除。 |
| static readonly [Model](../../groupdocs.conversion.options.load/cadlayoutscope/model) | 仅选择模型空间。 |

### 另见

* class [Enumeration](../../groupdocs.conversion.contracts/enumeration)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
