---
title: "PageSizeOptions"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "表示支持页面大小的选项"
type: docs
weight: 2990
url: /zh/net/groupdocs.conversion.options/pagesizeoptions/
---
## PageSizeOptions class

表示支持页面大小的选项

```csharp
public sealed class PageSizeOptions : ValueObject
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PageSizeOptions](pagesizeoptions)() | 默认构造函数。将 [`PageSize`](./pagesize) 初始化为 [`Unset`](../pagesize/unset)。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [PageHeight](../../groupdocs.conversion.options/pagesizeoptions/pageheight) { get; set; } | 在转换之前要应用的页面高度（单位：点）。设置后，[`PageSize`](./pagesize) 将自动更改为 [`Custom`](../pagesize/custom)。 |
| [PageSize](../../groupdocs.conversion.options/pagesizeoptions/pagesize) { get; set; } | 实现 [`PageSize`](../pagesize) |
| [PageWidth](../../groupdocs.conversion.options/pagesizeoptions/pagewidth) { get; set; } | 在转换之前要应用的页面宽度（单位：点）。设置后，[`PageSize`](./pagesize) 将自动更改为 [`Custom`](../pagesize/custom)。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 确定两个对象实例是否相等。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 确定两个对象实例是否相等。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | 充当默认的哈希函数。 |

### 另见

* class [ValueObject](../../groupdocs.conversion.contracts/valueobject)
* namespace [GroupDocs.Conversion.Options](../../groupdocs.conversion.options)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
