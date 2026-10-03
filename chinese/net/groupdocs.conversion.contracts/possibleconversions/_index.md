---
title: "PossibleConversions"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "表示针对特定源文件格式支持的转换对的映射关系"
type: docs
weight: 510
url: /zh/net/groupdocs.conversion.contracts/possibleconversions/
---
## PossibleConversions class

表示针对特定源文件格式支持的转换对的映射关系

```csharp
public sealed class PossibleConversions : ValueObject
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [All](../../groupdocs.conversion.contracts/possibleconversions/all) { get; } | 所有目标文件类型以及主/次标志 IEnumerable of [`TargetConversion`](../targetconversion) |
| [Item](../../groupdocs.conversion.contracts/possibleconversions/item) { get; } | 返回指定目标文件类型的目标转换（2 个索引器） |
| [LoadOptions](../../groupdocs.conversion.contracts/possibleconversions/loadoptions) { get; } | 可用于从当前类型转换的预定义加载选项 |
| [Primary](../../groupdocs.conversion.contracts/possibleconversions/primary) { get; } | 主要目标文件类型 |
| [Secondary](../../groupdocs.conversion.contracts/possibleconversions/secondary) { get; } | 次要目标文件类型 |
| [Source](../../groupdocs.conversion.contracts/possibleconversions/source) { get; } | 源文件格式 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 确定两个对象实例是否相等。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 确定两个对象实例是否相等。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | 充当默认的哈希函数。 |

### 另见

* class [ValueObject](../valueobject)
* namespace [GroupDocs.Conversion.Contracts](../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
