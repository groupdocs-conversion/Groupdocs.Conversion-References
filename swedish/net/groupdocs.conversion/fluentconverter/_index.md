---
title: "FluentConverter"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Klass för flytande konverteringsinställning."
type: docs
weight: 1580
url: /sv/net/groupdocs.conversion/fluentconverter/
---
## FluentConverter class

Klass för flytande konverteringsinställning.

```csharp
public static class FluentConverter
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [Load](../../groupdocs.conversion/fluentconverter/load#load_1)(Func&lt;Stream&gt;) | Konfigurera källdokumentström |
| static [Load](../../groupdocs.conversion/fluentconverter/load#load)(Func&lt;Stream[]&gt;) | Konfigurera uppsättning av källdokumentströmmar |
| static [Load](../../groupdocs.conversion/fluentconverter/load#load_2)(string) | Konfigurera källdokument för konvertering |
| static [Load](../../groupdocs.conversion/fluentconverter/load#load_3)(string[]) | Konfigurera uppsättning av källdokument |
| static [WithEvents](../../groupdocs.conversion/fluentconverter/withevents)(Action&lt;ConversionEvents&gt;) | Entry-stage-variant av den flytande kedjan som startar med konverteringslivscykelns händelsehanterare. Sitter på samma startstadium som [`WithSettings`](./withsettings), och den resulterande [`ConversionEvents`](../conversionevents)-samlingen avfyras vid varje konverteringskörning av konverteraren. |
| static [WithSettings](../../groupdocs.conversion/fluentconverter/withsettings)(Func&lt;ConverterSettings&gt;) | Konfigurera konverteringsinställningar |

### Anmärkningar

Exempel på användning av flytande konvertering:

```csharp
var converter = FluentConverter.Create();
```

```csharp
FluentConverter.Load("")
    .ConvertTo("")
    .Convert();
```

```csharp
// Rekommenderas: samla ihop hanterare via WithEvents i det tidiga stadiet (innan Load).
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
// Per-sida spegel: per-sida hanterare via WithEvents i det tidiga stadiet.
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
// Legacy-kedjan kompileras fortfarande oförändrad (nu stödd av de föråldrade staged-gränssnitten):
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

### Se även

* namespace [GroupDocs.Conversion](../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
