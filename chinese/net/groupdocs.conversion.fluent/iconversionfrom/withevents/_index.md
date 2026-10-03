---
title: "WithEvents"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "在一个 ConversionEventsgroupdocs.conversion/conversionevents 包上注册转换生命周期事件处理程序，该包在转换器的整个生命周期内存在，并在每次转换运行时触发。可以在 WithSettingsgroupdocs.conversion.fluent/iconversionsettings/withsettings 之前或之后调用。多次调用会累积：相同的内部包被传递给每个 configure 操作，因此在较早调用中设置的处理程序会保留下来，除非被后来的调用覆盖。"
type: docs
weight: 20
url: /zh/net/groupdocs.conversion.fluent/iconversionfrom/withevents/
---
## IConversionFrom.WithEvents method

在一个 [`ConversionEvents`](../../../groupdocs.conversion/conversionevents) 包上注册转换生命周期事件处理程序，该包在转换器的整个生命周期内存在，并在每次转换运行时触发。可以在 [`WithSettings`](../../iconversionsettings/withsettings) 之前或之后调用。多次调用会累积：相同的内部包被传递给每个 *configure* 操作，因此在较早调用中设置的处理程序会保留下来，除非被后来的调用覆盖。

```csharp
public IConversionFrom WithEvents(Action<ConversionEvents> configure)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| configure | Action`1 | 会修改事件包的 Action。 |

### 返回值

此阶段用于使后续的入口阶段调用或 `Load` 能够链式调用。

### 另见

* class [ConversionEvents](../../../groupdocs.conversion/conversionevents)
* interface [IConversionFrom](../../iconversionfrom)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
