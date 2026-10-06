---
title: "FluentConverter sınıfı"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Akıcı bir dönüşüm kurulumunu temsil eder."
type: docs
url: /tr/python-net/groupdocs.conversion/fluentconverter/
is_root: false
weight: 120
---


## FluentConverter class

Akıcı bir dönüşüm kurulumunu temsil eder.

Örnek akıcı dönüşüm kullanımı:

```csharp
var converter = FluentConverter.Create();
```

```csharp
FluentConverter.Load("")
    .ConvertTo("")
    .Convert();
```

```csharp
// Önerilen: erken aşamada (Load'dan önce) WithEvents aracılığıyla işleyicileri birleştirin.
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
// Sayfa başına yansıma: erken aşamada WithEvents aracılığıyla sayfa başı işleyicileri.
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
// Eski zincir hâlâ değişmeden derleniyor (artık eski aşamalı arabirimler tarafından destekleniyor):
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

FluentConverter türü aşağıdaki üyeleri sunar:

### Yöntemler
| Yöntem | Açıklama |
| :- | :- |
| [load](/conversion/python-net/groupdocs.conversion/fluentconverter/load/#file_name) | Dönüşüm için kaynak belgeyi yapılandır. |
| [load](/conversion/python-net/groupdocs.conversion/fluentconverter/load/#file_name) | Kaynak belgeler kümesini yapılandır. |
| [load](/conversion/python-net/groupdocs.conversion/fluentconverter/load/#document_stream_provider) | Kaynak belge akışını yapılandır. |
| [load](/conversion/python-net/groupdocs.conversion/fluentconverter/load/#document_stream_provider) | Kaynak belge akışları kümesini yapılandır. |
| [load_file](/conversion/python-net/groupdocs.conversion/fluentconverter/load_file/) |  |
| [load_files](/conversion/python-net/groupdocs.conversion/fluentconverter/load_files/) |  |
| [load_func](/conversion/python-net/groupdocs.conversion/fluentconverter/load_func/) |  |
| [load_string](/conversion/python-net/groupdocs.conversion/fluentconverter/load_string/) |  |
| [load_strings](/conversion/python-net/groupdocs.conversion/fluentconverter/load_strings/) |  |
| [with_events](/conversion/python-net/groupdocs.conversion/fluentconverter/with_events/#configure) | Giriş aşamasında dönüşüm yaşam döngüsü olay işleyicileriyle akıcı bir zincir başlatır. |
| [with_settings](/conversion/python-net/groupdocs.conversion/fluentconverter/with_settings/#settings_provider) | Dönüşüm ayarlarını yapılandır. |

### Ayrıca Bakınız
* module [`groupdocs.conversion`](/conversion/python-net/groupdocs.conversion/)
