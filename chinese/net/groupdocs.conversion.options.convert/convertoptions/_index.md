---
title: "ConvertOptions"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "通用转换选项类。"
type: docs
weight: 1760
url: /zh/net/groupdocs.conversion.options.convert/convertoptions/
---
## ConvertOptions class

通用转换选项类。

```csharp
public abstract class ConvertOptions : ValueObject, ICloneable, IConvertOptions
```

## 属性

| 名称 | 描述 |
| --- | --- |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | 实现 [`Format`](../iconvertoptions/format) |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | 克隆当前选项实例。 |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 确定两个对象实例是否相等。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 确定两个对象实例是否相等。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | 充当默认的哈希函数。 |

### 另见

* class [ValueObject](../../groupdocs.conversion.contracts/valueobject)
* interface [IConvertOptions](../iconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
