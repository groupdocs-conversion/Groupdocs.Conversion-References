---
title: "WithEvents"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "在一个 ConversionEventsgroupdocs.conversion/conversionevents 包上注册转换生命周期事件处理程序，该包在转换器的整个生命周期内存在，并在每次转换运行时触发。它位于与 WithSettingsgroupdocs.conversion.fluent/iconversionsettings/withsettings 相同的入口阶段。多次调用会累积，同一个内部包会传递给每个 configure 操作，因此在早期调用中设置的处理程序会保留，除非被后续调用覆盖。"
type: docs
weight: 10
url: /zh/net/groupdocs.conversion.fluent/iconversionsettings/withevents/
---
## IConversionSettings.WithEvents method

在一个 [`ConversionEvents`](../../../groupdocs.conversion/conversionevents) 包上注册转换生命周期事件处理程序，该包在转换器的整个生命周期内存在，并在每次转换运行时触发。它位于与 [`WithSettings`](../withsettings) 相同的入口阶段。多次调用会累积：同一个内部包会传递给每个 *configure* 操作，因此在早期调用中设置的处理程序会保留，除非被后续调用覆盖。

```csharp
public IConversionFrom WithEvents(Action<ConversionEvents> configure)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| configure | Action`1 | 会修改事件包的 Action。 |

### 返回值

源选择阶段，以便可以链式调用 `Load`。

### 另见

* interface [IConversionFrom](../../iconversionfrom)
* class [ConversionEvents](../../../groupdocs.conversion/conversionevents)
* interface [IConversionSettings](../../iconversionsettings)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
