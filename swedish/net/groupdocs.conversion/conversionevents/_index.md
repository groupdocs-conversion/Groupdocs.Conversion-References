---
title: "ConversionEvents"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Samlar konverteringslivscykelns händelsehanterare. Skicka en instans till Converter./converter‑konstruktörernas events‑parameter eller till den flytande WithEvents‑metoden. Föredra detta framför de enskilda ConverterSettings./convertersettings‑hanteraregenskaperna som är föråldrade."
type: docs
weight: 850
url: /sv/net/groupdocs.conversion/conversionevents/
---
## ConversionEvents class

Samlar konverteringslivscykelns händelsehanterare. Skicka en instans till [`Converter`](../converter)‑konstruktörens `events`‑parameter eller till den flytande `WithEvents`‑metoden. Föredra detta framför de enskilda [`ConverterSettings`](../convertersettings)‑hanteraregenskaperna, som är föråldrade.

```csharp
public sealed class ConversionEvents
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [ConversionEvents](conversionevents)() | Standardkonstruktören. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [OnCompressionCompleted](../../groupdocs.conversion/conversionevents/oncompressioncompleted) { get; set; } | Utlöst när komprimering av konverteringsutdata slutförs. Anropas endast i byggen som inkluderar komprimeringspipeline (LIB_ZIP). |
| [OnConversionCompleted](../../groupdocs.conversion/conversionevents/onconversioncompleted) { get; set; } | Utlöst en gång när konverteringskörningen avslutas, oavsett om den lyckas eller misslyckas. |
| [OnConversionProgress](../../groupdocs.conversion/conversionevents/onconversionprogress) { get; set; } | Utlöst periodiskt med konverteringsförlopp som en procentsats (0–100). |
| [OnConversionStarted](../../groupdocs.conversion/conversionevents/onconversionstarted) { get; set; } | Utlöst en gång i början av konverteringskörningen, innan något dokument bearbetas. |
| [OnDocumentConverted](../../groupdocs.conversion/conversionevents/ondocumentconverted) { get; set; } | Utlöses en gång per hel-dokumentkonvertering som slutförs framgångsrikt. |
| [OnDocumentFailed](../../groupdocs.conversion/conversionevents/ondocumentfailed) { get; set; } | Utlöses en gång per hel-dokumentkonvertering som misslyckas. |
| [OnFontSubstituted](../../groupdocs.conversion/conversionevents/onfontsubstituted) { get; set; } | Utlöses när ett teckensnitt som refereras av källdokumentet inte är tillgängligt och ersätts (antingen av en kundtillhandahållen [`FontSubstitute`](../../groupdocs.conversion.contracts/fontsubstitute)-regel, av det konfigurerade standardteckensnittet, eller av konverteringspipelinens interna reserv). |
| [OnPageConverted](../../groupdocs.conversion/conversionevents/onpageconverted) { get; set; } | Utlöses en gång per sida när en per-sida konvertering slutförs framgångsrikt. |
| [OnPageFailed](../../groupdocs.conversion/conversionevents/onpagefailed) { get; set; } | Utlöses en gång per sida när en per-sida konvertering misslyckas. |

### Se även

* namespace [GroupDocs.Conversion](../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
