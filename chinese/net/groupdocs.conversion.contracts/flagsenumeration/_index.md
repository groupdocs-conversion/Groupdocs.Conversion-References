---
title: "FlagsEnumeration"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "表示用于创建支持按位标志操作的枚举的抽象基类。"
type: docs
weight: 220
url: /zh/net/groupdocs.conversion.contracts/flagsenumeration/
---
## FlagsEnumeration class

表示用于创建支持按位标志操作的枚举的抽象基类。

```csharp
public abstract class FlagsEnumeration : Enumeration
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | 将当前对象与其他对象进行比较。 |
| virtual [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(Enumeration) | 确定两个对象实例是否相等。 |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | 确定两个对象实例是否相等。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | 充当默认的哈希函数。 |
| virtual [HasFlag&lt;T&gt;](../../groupdocs.conversion.contracts/flagsenumeration/hasflag)(T) | 检查当前标志是否具有指定的标志。 |
| virtual [HasFlagValue](../../groupdocs.conversion.contracts/flagsenumeration/hasflagvalue)(int) | 检查当前标志是否具有指定的值。 |
| override [ToString](../../groupdocs.conversion.contracts/flagsenumeration/tostring)() | 将当前对象转换为字符串。 |
| static [Combine&lt;T&gt;](../../groupdocs.conversion.contracts/flagsenumeration/combine)(T, T) | 将两个标志枚举合并为一个。 |

### 另见

* class [Enumeration](../enumeration)
* namespace [GroupDocs.Conversion.Contracts](../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
