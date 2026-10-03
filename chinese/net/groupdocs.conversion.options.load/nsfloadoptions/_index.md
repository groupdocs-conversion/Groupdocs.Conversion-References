---
title: "NsfLoadOptions"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "加载 Nsf 文档的选项。"
type: docs
weight: 2690
url: /zh/net/groupdocs.conversion.options.load/nsfloadoptions/
---
## NsfLoadOptions class

加载 Nsf 文档的选项。

```csharp
public sealed class NsfLoadOptions : LoadOptions, IDocumentsContainerLoadOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [NsfLoadOptions](nsfloadoptions)() | 初始化 [`NsfLoadOptions`](../nsfloadoptions) 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [ConvertOwned](../../groupdocs.conversion.options.load/nsfloadoptions/convertowned) { get; } | 实现 [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) 只读。设置为 true。拥有的文档将被转换 |
| [ConvertOwner](../../groupdocs.conversion.options.load/nsfloadoptions/convertowner) { get; } | 实现 [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) 只读。设置为 false。所有者将不会被转换 |
| [Depth](../../groupdocs.conversion.options.load/nsfloadoptions/depth) { get; set; } | 实现 [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth) 默认值：3 |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | 输入文档的文件类型。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.load/nsfloadoptions/clone)() | 克隆当前实例。 |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 确定两个对象实例是否相等。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 确定两个对象实例是否相等。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | 充当默认的哈希函数。 |

### 另见

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
