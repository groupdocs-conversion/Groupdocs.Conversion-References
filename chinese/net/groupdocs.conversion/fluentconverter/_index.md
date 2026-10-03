---
title: "FluentConverter"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "用于流式转换设置的类。"
type: docs
weight: 1580
url: /zh/net/groupdocs.conversion/fluentconverter/
---
## FluentConverter class

用于流式转换设置的类。

```csharp
public static class FluentConverter
```

## 方法

| 名称 | 描述 |
| --- | --- |
| static [Load](../../groupdocs.conversion/fluentconverter/load#load_1)(Func&lt;Stream&gt;) | 配置源文档流 |
| static [Load](../../groupdocs.conversion/fluentconverter/load#load)(Func&lt;Stream[]&gt;) | 配置一组源文档流 |
| static [Load](../../groupdocs.conversion/fluentconverter/load#load_2)(string) | 配置用于转换的源文档 |
| static [Load](../../groupdocs.conversion/fluentconverter/load#load_3)(string[]) | 配置一组源文档 |
| static [WithEvents](../../groupdocs.conversion/fluentconverter/withevents)(Action&lt;ConversionEvents&gt;) | 流式链的入口阶段变体，以转换生命周期事件处理程序开始。位于与[`WithSettings`](./withsettings)相同的入口阶段，生成的[`ConversionEvents`](../conversionevents)包在转换器的每次转换运行时触发。 |
| static [WithSettings](../../groupdocs.conversion/fluentconverter/withsettings)(Func&lt;ConverterSettings&gt;) | 配置转换设置 |

### 备注

流式转换使用示例：

```csharp
var converter = FluentConverter.Create();
```

```csharp
FluentConverter.Load("")
    .ConvertTo("")
    .Convert();
```

```csharp
// 建议：在早期阶段（Load 之前）通过 WithEvents 聚合处理程序。
FluentConverter
    .WithEvents(e =>
    {
        e.OnDocumentConverted = ctx       => Console.WriteLine($"Done: {ctx.SourceFileName}");
        e.OnDocumentFailed    = (ctx, ex) => Console.Error.WriteLine(ex.Message);
    })
    .Load("input.docx")
    .ConvertTo("output.pdf").WithOptions(new PdfConvertOptions())
    .Convert();
```

```csharp
// 逐页镜像：在早期阶段通过 WithEvents 使用逐页处理程序。
FluentConverter
    .WithEvents(e =>
    {
        e.OnPageConverted = ctx       => Console.WriteLine($"page {ctx.Page} done");
        e.OnPageFailed    = (ctx, ex) => Console.Error.WriteLine($"page {ctx.Page}: {ex.Message}");
    })
    .Load("input.pdf")
    .ConvertByPageTo(ctx => new FileStream($"page-{ctx.Page}.png", FileMode.Create))
    .WithOptions(new ImageConvertOptions { Format = ImageFileType.Png })
    .Convert();
```

```csharp
// 旧版链仍然可以不变编译（现在由已废弃的分阶段接口支持）：
FluentConverter.WithSettings(() => new ConverterSettings())
    .Load("").WithOptions(new PdfLoadOptions())
    .ConvertTo("").WithOptions(new PdfConvertOptions())
    .OnConversionCompleted(convertedDocumentStream => { })
    .Convert();
```

```csharp
FluentConverter.Load("").GetPossibleConversions();
FluentConverter.Load("").GetDocumentInfo();
FluentConverter.Load("").WithOptions(new PdfLoadOptions()).GetPossibleConversions();
FluentConverter.Load("").WithOptions(new PdfLoadOptions()).GetDocumentInfo();
```

### 另见

* namespace [GroupDocs.Conversion](../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
