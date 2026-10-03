---
title: "WithEvents"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "入口阶段变体的流式链，以转换生命周期事件处理程序开始。它位于与 WithSettingsgroupdocs.conversion/fluentconverter/withsettings 相同的入口阶段，生成的 ConversionEventsgroupdocs.conversion/conversionevents 包会在转换器的每次转换运行时触发。"
type: docs
weight: 20
url: /zh/net/groupdocs.conversion/fluentconverter/withevents/
---
## FluentConverter.WithEvents method

入口阶段变体的流式链，以转换生命周期事件处理程序开始。它位于与 [`WithSettings`](../withsettings) 相同的入口阶段，生成的 [`ConversionEvents`](../../conversionevents) 包会在转换器的每次转换运行时触发。

```csharp
public static IConversionFrom WithEvents(Action<ConversionEvents> configure)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| configure | Action`1 | 会修改事件包的 Action。 |

### 返回值

源选择阶段，以便可以链式调用 `Load`。

### 另见

* interface [IConversionFrom](../../../groupdocs.conversion.fluent/iconversionfrom)
* class [ConversionEvents](../../conversionevents)
* class [FluentConverter](../../fluentconverter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
