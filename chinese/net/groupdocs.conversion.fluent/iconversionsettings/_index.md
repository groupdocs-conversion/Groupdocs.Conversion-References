---
title: "IConversionSettings"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "在加载之前的入口阶段设置转换设置或事件。"
type: docs
weight: 1540
url: /zh/net/groupdocs.conversion.fluent/iconversionsettings/
---
## IConversionSettings interface

在入口阶段（`Load`之前）设置转换设置或事件。

```csharp
public interface IConversionSettings
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [WithEvents](../../groupdocs.conversion.fluent/iconversionsettings/withevents)(Action&lt;ConversionEvents&gt;) | 在一个 [`ConversionEvents`](../../groupdocs.conversion/conversionevents) 包上注册转换生命周期事件处理程序，该包在转换器的整个生命周期内存在，并在每次转换运行时触发。它位于与 [`WithSettings`](./withsettings) 相同的入口阶段。多次调用会累积：相同的内部包会传递给每个 *configure* 操作，因此在较早调用中设置的处理程序会保留，除非被后续调用覆盖。 |
| [WithSettings](../../groupdocs.conversion.fluent/iconversionsettings/withsettings)(Func&lt;ConverterSettings&gt;) | 设置转换器设置 |

### 另见

* namespace [GroupDocs.Conversion.Fluent](../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
