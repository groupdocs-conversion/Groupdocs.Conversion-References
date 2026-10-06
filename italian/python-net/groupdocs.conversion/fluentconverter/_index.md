---
title: "Classe FluentConverter"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Rappresenta una configurazione fluida della conversione."
type: docs
url: /it/python-net/groupdocs.conversion/fluentconverter/
is_root: false
weight: 120
---


## FluentConverter class

Rappresenta una configurazione fluida della conversione.

Esempio di utilizzo fluente della conversione:

```csharp
var converter = FluentConverter.Create();
```

```csharp
FluentConverter.Load("")
    .ConvertTo("")
    .Convert();
```

```csharp
// Consigliato: aggregare i gestori tramite WithEvents nella fase iniziale (prima del caricamento).
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
// Specchio per pagina: gestori per pagina tramite WithEvents nella fase iniziale.
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
// La catena legacy si compila ancora invariata (ora supportata dalle interfacce stagionali obsolete):
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

Il tipo FluentConverter espone i seguenti membri:

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [load](/conversion/python-net/groupdocs.conversion/fluentconverter/load/#file_name) | Configura il documento sorgente per la conversione. |
| [load](/conversion/python-net/groupdocs.conversion/fluentconverter/load/#file_name) | Configura l'insieme di documenti sorgente. |
| [load](/conversion/python-net/groupdocs.conversion/fluentconverter/load/#document_stream_provider) | Configura lo stream del documento sorgente. |
| [load](/conversion/python-net/groupdocs.conversion/fluentconverter/load/#document_stream_provider) | Configura un insieme di stream di documenti sorgente. |
| [load_file](/conversion/python-net/groupdocs.conversion/fluentconverter/load_file/) |  |
| [load_files](/conversion/python-net/groupdocs.conversion/fluentconverter/load_files/) |  |
| [load_func](/conversion/python-net/groupdocs.conversion/fluentconverter/load_func/) |  |
| [load_string](/conversion/python-net/groupdocs.conversion/fluentconverter/load_string/) |  |
| [load_strings](/conversion/python-net/groupdocs.conversion/fluentconverter/load_strings/) |  |
| [with_events](/conversion/python-net/groupdocs.conversion/fluentconverter/with_events/#configure) | Avvia una catena fluente nella fase di ingresso con gestori di eventi del ciclo di vita della conversione. |
| [with_settings](/conversion/python-net/groupdocs.conversion/fluentconverter/with_settings/#settings_provider) | Configura le impostazioni di conversione. |

### Vedi anche
* module [`groupdocs.conversion`](/conversion/python-net/groupdocs.conversion/)
