---
title: "ConversionEvents"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "聚合转换生命周期事件处理程序。将实例传递给 Converter./converter 构造函数的 events 参数或流式 WithEvents 方法。建议使用它而不是已过时的单独的 ConverterSettings./convertersettings 处理程序属性。"
type: docs
weight: 850
url: /zh/net/groupdocs.conversion/conversionevents/
---
## ConversionEvents class

聚合转换生命周期事件处理程序。将实例传递给 [`Converter`](../converter) 构造函数的 `events` 参数或流式 `WithEvents` 方法。建议使用它而不是已过时的单独的 [`ConverterSettings`](../convertersettings) 处理程序属性。

```csharp
public sealed class ConversionEvents
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [ConversionEvents](conversionevents)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [OnCompressionCompleted](../../groupdocs.conversion/conversionevents/oncompressioncompleted) { get; set; } | 在转换输出压缩完成时触发。仅在包含压缩管道 (LIB_ZIP) 的构建中调用。 |
| [OnConversionCompleted](../../groupdocs.conversion/conversionevents/onconversioncompleted) { get; set; } | 在转换运行结束时触发一次，无论成功或失败。 |
| [OnConversionProgress](../../groupdocs.conversion/conversionevents/onconversionprogress) { get; set; } | 定期触发，提供转换进度的百分比（0–100）。 |
| [OnConversionStarted](../../groupdocs.conversion/conversionevents/onconversionstarted) { get; set; } | 在转换运行开始时触发一次，在处理任何文档之前。 |
| [OnDocumentConverted](../../groupdocs.conversion/conversionevents/ondocumentconverted) { get; set; } | 在整个文档转换成功完成时触发一次。 |
| [OnDocumentFailed](../../groupdocs.conversion/conversionevents/ondocumentfailed) { get; set; } | 在整个文档转换失败时触发一次。 |
| [OnFontSubstituted](../../groupdocs.conversion/conversionevents/onfontsubstituted) { get; set; } | 当源文档引用的字体不可用且被替代时触发（可以是客户提供的[`FontSubstitute`](../../groupdocs.conversion.contracts/fontsubstitute)规则、配置的默认字体，或转换管道的内部回退）。 |
| [OnPageConverted](../../groupdocs.conversion/conversionevents/onpageconverted) { get; set; } | 在每页的逐页转换成功完成时触发一次。 |
| [OnPageFailed](../../groupdocs.conversion/conversionevents/onpagefailed) { get; set; } | 在每页的逐页转换失败时触发一次。 |

### 另见

* namespace [GroupDocs.Conversion](../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
