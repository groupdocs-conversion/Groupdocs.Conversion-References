---
title: "FluentConverter klasse"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Stelt een vloeiende conversieconfiguratie voor."
type: docs
url: /nl/python-net/groupdocs.conversion/fluentconverter/
is_root: false
weight: 120
---


## FluentConverter class

Stelt een vloeiende conversieconfiguratie voor.

Voorbeeld van vloeiende conversiegebruik:

```csharp
var converter = FluentConverter.Create();
```

```csharp
FluentConverter.Load("")
    .ConvertTo("")
    .Convert();
```

```csharp
// Aanbevolen: handlers aggregeren via WithEvents in een vroeg stadium (voor Load).
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
// Per-pagina spiegel: per-pagina handlers via WithEvents in een vroeg stadium.
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
// Legacy-keten compileert nog steeds ongewijzigd (nu ondersteund door de verouderde staged interfaces):
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

Het FluentConverter-type geeft de volgende leden weer:

### Methoden
| Methode | Beschrijving |
| :- | :- |
| [load](/conversion/python-net/groupdocs.conversion/fluentconverter/load/#file_name) | Configureer brondocument voor conversie. |
| [load](/conversion/python-net/groupdocs.conversion/fluentconverter/load/#file_name) | Configureer set van brondocumenten. |
| [load](/conversion/python-net/groupdocs.conversion/fluentconverter/load/#document_stream_provider) | Configureer brondocumentstroom. |
| [load](/conversion/python-net/groupdocs.conversion/fluentconverter/load/#document_stream_provider) | Configureer een set van brondocumentstromen. |
| [load_file](/conversion/python-net/groupdocs.conversion/fluentconverter/load_file/) |  |
| [load_files](/conversion/python-net/groupdocs.conversion/fluentconverter/load_files/) |  |
| [load_func](/conversion/python-net/groupdocs.conversion/fluentconverter/load_func/) |  |
| [load_string](/conversion/python-net/groupdocs.conversion/fluentconverter/load_string/) |  |
| [load_strings](/conversion/python-net/groupdocs.conversion/fluentconverter/load_strings/) |  |
| [with_events](/conversion/python-net/groupdocs.conversion/fluentconverter/with_events/#configure) | Start een vloeiende keten in de instapfase met conversielevenscyclus‑eventhandlers. |
| [with_settings](/conversion/python-net/groupdocs.conversion/fluentconverter/with_settings/#settings_provider) | Configureer conversie‑instellingen. |

### Zie ook
* module [`groupdocs.conversion`](/conversion/python-net/groupdocs.conversion/)
