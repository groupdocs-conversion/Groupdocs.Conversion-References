---
title: "ConversionEvents"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Aggrega i gestori degli eventi del ciclo di vita della conversione. Passa un'istanza al parametro events dei costruttori Converter./converter o al metodo fluente WithEvents. Preferisci questo rispetto alle singole proprietà handler di ConverterSettings./convertersettings, che sono obsolete."
type: docs
weight: 850
url: /it/net/groupdocs.conversion/conversionevents/
---
## ConversionEvents class

Aggrega i gestori degli eventi del ciclo di vita della conversione. Passa un'istanza al parametro `events` del costruttore [`Converter`](../converter) o al metodo fluente `WithEvents`. Preferisci questo rispetto alle singole proprietà handler di [`ConverterSettings`](../convertersettings), che sono obsolete.

```csharp
public sealed class ConversionEvents
```

## Costruttori

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [ConversionEvents](conversionevents)() | Il costruttore predefinito. |

## Proprietà

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [OnCompressionCompleted](../../groupdocs.conversion/conversionevents/oncompressioncompleted) { get; set; } | Attivato quando la compressione dell'output della conversione è completata. Viene invocato solo nelle build che includono la pipeline di compressione (LIB_ZIP). |
| [OnConversionCompleted](../../groupdocs.conversion/conversionevents/onconversioncompleted) { get; set; } | Attivato una volta quando l'esecuzione della conversione termina, indipendentemente dal successo o dal fallimento. |
| [OnConversionProgress](../../groupdocs.conversion/conversionevents/onconversionprogress) { get; set; } | Attivato periodicamente con l'avanzamento della conversione in percentuale (0–100). |
| [OnConversionStarted](../../groupdocs.conversion/conversionevents/onconversionstarted) { get; set; } | Attivato una volta all'inizio dell'esecuzione della conversione, prima che venga elaborato qualsiasi documento. |
| [OnDocumentConverted](../../groupdocs.conversion/conversionevents/ondocumentconverted) { get; set; } | Attivato una volta per ogni conversione dell'intero documento che si completa con successo. |
| [OnDocumentFailed](../../groupdocs.conversion/conversionevents/ondocumentfailed) { get; set; } | Attivato una volta per ogni conversione dell'intero documento che fallisce. |
| [OnFontSubstituted](../../groupdocs.conversion/conversionevents/onfontsubstituted) { get; set; } | Attivato quando un font referenziato dal documento sorgente non è disponibile e viene sostituito (sia da una regola [`FontSubstitute`](../../groupdocs.conversion.contracts/fontsubstitute) fornita dal cliente, dal font predefinito configurato, o dal fallback interno della pipeline di conversione). |
| [OnPageConverted](../../groupdocs.conversion/conversionevents/onpageconverted) { get; set; } | Attivato una volta per pagina quando una conversione per pagina si completa con successo. |
| [OnPageFailed](../../groupdocs.conversion/conversionevents/onpagefailed) { get; set; } | Attivato una volta per pagina quando una conversione per pagina fallisce. |

### IConversionConvertOptions

* namespace [GroupDocs.Conversion](../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
