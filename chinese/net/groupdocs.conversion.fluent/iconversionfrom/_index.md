---
title: "IConversionFrom"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "设置转换源"
type: docs
weight: 1440
url: /zh/net/groupdocs.conversion.fluent/iconversionfrom/
---
## IConversionFrom interface

设置转换源

```csharp
public interface IConversionFrom
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [Load](../../groupdocs.conversion.fluent/iconversionfrom/load#load_1)(Func&lt;Stream&gt;) | 设置源文档流 |
| [Load](../../groupdocs.conversion.fluent/iconversionfrom/load#load)(Func&lt;Stream[]&gt;) | 设置源文档流数组 |
| [Load](../../groupdocs.conversion.fluent/iconversionfrom/load#load_2)(string) | 设置源文档文件名 |
| [Load](../../groupdocs.conversion.fluent/iconversionfrom/load#load_3)(string[]) | 设置源文档数组 |
| [WithEvents](../../groupdocs.conversion.fluent/iconversionfrom/withevents)(Action&lt;ConversionEvents&gt;) | 在一个 [`ConversionEvents`](../../groupdocs.conversion/conversionevents) 包上注册转换生命周期事件处理程序，该包在转换器的整个生命周期内存在，并在每次转换运行时触发。可以在 [`WithSettings`](../iconversionsettings/withsettings) 之前或之后调用。多次调用会累积：相同的内部包会传递给每个 *configure* 操作，因此在较早调用中设置的处理程序会保留，除非被后续调用覆盖。 |

### 另见

* namespace [GroupDocs.Conversion.Fluent](../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
