---
title: "FluentConverter"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Classe per la configurazione fluida della conversione."
type: docs
weight: 1580
url: /it/net/groupdocs.conversion/fluentconverter/
---
## FluentConverter class

Classe per la configurazione fluida della conversione.

```csharp
public static class FluentConverter
```

## Vedi anche

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| static [Load](../../groupdocs.conversion/fluentconverter/load#load_1)(Func&lt;Stream&gt;) | Configura lo stream del documento sorgente |
| static [Load](../../groupdocs.conversion/fluentconverter/load#load)(Func&lt;Stream[]&gt;) | Configura l'insieme di stream dei documenti sorgente |
| static [Load](../../groupdocs.conversion/fluentconverter/load#load_2)(string) | Configura il documento sorgente per la conversione |
| static [Load](../../groupdocs.conversion/fluentconverter/load#load_3)(string[]) | Configura l'insieme di documenti sorgente |
| static [WithEvents](../../groupdocs.conversion/fluentconverter/withevents)(Action&lt;ConversionEvents&gt;) | Variante di fase di ingresso della catena fluente che inizia con i gestori di eventi del ciclo di vita della conversione. Si trova nella stessa fase di ingresso di [`WithSettings`](./withsettings) e il contenitore risultante di [`ConversionEvents`](../conversionevents) si attiva ad ogni esecuzione di conversione da parte del convertitore. |
| static [WithSettings](../../groupdocs.conversion/fluentconverter/withsettings)(Func&lt;ConverterSettings&gt;) | Configura le impostazioni di conversione |

### Osservazioni

Esempio di utilizzo della conversione fluente:

```csharp
var converter = FluentConverter.Create();
```

```csharp
FluentConverter.Load("")
    .ConvertTo("")
    .Convert();
```

```csharp
// Consigliato: aggregare i gestori tramite WithEvents nella fase iniziale (prima di Load).
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
// La catena legacy si compila ancora invariata (ora supportata dalle interfacce stagionate obsolete):
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

### IConversionConvertOptions

* namespace [GroupDocs.Conversion](../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
