---
title: "FluentConverter 类"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "表示流畅的转换设置。"
type: docs
url: /zh/python-net/groupdocs.conversion/fluentconverter/
is_root: false
weight: 120
---


## FluentConverter class

表示流畅的转换设置。

示例流畅转换用法：

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
// 每页镜像：在早期阶段通过 WithEvents 使用每页处理程序。
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
// 旧版链仍然保持不变编译（现在由已废弃的分阶段接口支持）：
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

FluentConverter 类型公开以下成员：

### 方法
| 方法 | 描述 |
| :- | :- |
| [load](/conversion/python-net/groupdocs.conversion/fluentconverter/load/#file_name) | 配置用于转换的源文档。 |
| [load](/conversion/python-net/groupdocs.conversion/fluentconverter/load/#file_name) | 配置源文档集合。 |
| [load](/conversion/python-net/groupdocs.conversion/fluentconverter/load/#document_stream_provider) | 配置源文档流。 |
| [load](/conversion/python-net/groupdocs.conversion/fluentconverter/load/#document_stream_provider) | 配置一组源文档流。 |
| [load_file](/conversion/python-net/groupdocs.conversion/fluentconverter/load_file/) |  |
| [load_files](/conversion/python-net/groupdocs.conversion/fluentconverter/load_files/) |  |
| [load_func](/conversion/python-net/groupdocs.conversion/fluentconverter/load_func/) |  |
| [load_string](/conversion/python-net/groupdocs.conversion/fluentconverter/load_string/) |  |
| [load_strings](/conversion/python-net/groupdocs.conversion/fluentconverter/load_strings/) |  |
| [with_events](/conversion/python-net/groupdocs.conversion/fluentconverter/with_events/#configure) | 在入口阶段使用转换生命周期事件处理程序启动流畅链。 |
| [with_settings](/conversion/python-net/groupdocs.conversion/fluentconverter/with_settings/#settings_provider) | 配置转换设置。 |

### 另见
* module [`groupdocs.conversion`](/conversion/python-net/groupdocs.conversion/)
