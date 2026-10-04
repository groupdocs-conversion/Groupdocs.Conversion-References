---
title: "FluentConverter"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Klasse voor fluente conversie-configuratie."
type: docs
weight: 1580
url: /nl/net/groupdocs.conversion/fluentconverter/
---
## FluentConverter class

Klasse voor fluente conversie-configuratie.

```csharp
public static class FluentConverter
```

## Methoden

| Naam | Beschrijving |
| --- | --- |
| static [Load](../../groupdocs.conversion/fluentconverter/load#load_1)(Func&lt;Stream&gt;) | Configureer brondocumentstroom |
| static [Load](../../groupdocs.conversion/fluentconverter/load#load)(Func&lt;Stream[]&gt;) | Configureer set van brondocumentstromen |
| static [Load](../../groupdocs.conversion/fluentconverter/load#load_2)(string) | Configureer brondocument voor conversie |
| static [Load](../../groupdocs.conversion/fluentconverter/load#load_3)(string[]) | Configureer set van brondocumenten |
| static [WithEvents](../../groupdocs.conversion/fluentconverter/withevents)(Action&lt;ConversionEvents&gt;) | Entry‑stage variant van de fluent chain die start met conversie‑levenscyclus‑eventhandlers. Zit op hetzelfde entry‑stage als [`WithSettings`](./withsettings), en de resulterende [`ConversionEvents`](../conversionevents) bag wordt geactiveerd bij elke conversierun van de converter. |
| static [WithSettings](../../groupdocs.conversion/fluentconverter/withsettings)(Func&lt;ConverterSettings&gt;) | Configureer conversie-instellingen |

### Opmerkingen

Voorbeeld van fluent conversiegebruik:

```csharp
var converter = FluentConverter.Create();
```

```csharp
FluentConverter.Load("")
    .ConvertTo("")
    .Convert();
```

```csharp
// Aanbevolen: verzamel handlers via WithEvents in een vroeg stadium (voor Load).
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
// Legacy chain compileert nog steeds ongewijzigd (nu ondersteund door de verouderde staged interfaces):
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

### Zie ook

* namespace [GroupDocs.Conversion](../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
