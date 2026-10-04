---
title: "PdfRecognitionMode"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Consente di controllare come un documento PDF viene convertito in un documento di elaborazione testi."
type: docs
weight: 2160
url: /it/net/groupdocs.conversion.options.convert/pdfrecognitionmode/
---
## PdfRecognitionMode class

Consente di controllare come un documento PDF viene convertito in un documento di elaborazione testi.

```csharp
public sealed class PdfRecognitionMode : Enumeration
```

## Vedi anche

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Confronta l'oggetto corrente con un altro. |
| virtual [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(Enumeration) | Determina se due istanze di oggetti sono uguali. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Determina se due istanze di oggetti sono uguali. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Funziona come funzione hash predefinita. |
| override [ToString](../../groupdocs.conversion.contracts/enumeration/tostring)() | Restituisce una stringa che rappresenta l'oggetto corrente. |

## Campi

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| static readonly [Flow](../../groupdocs.conversion.options.convert/pdfrecognitionmode/flow) | Modalità di riconoscimento completa, il motore esegue il raggruppamento e l'analisi a più livelli per ripristinare l'intento dell'autore del documento originale e produrre un documento massimamente modificabile. L'aspetto negativo è che il documento di output potrebbe apparire diverso dal file PDF originale. |
| static readonly [Textbox](../../groupdocs.conversion.options.convert/pdfrecognitionmode/textbox) | Questa modalità è veloce e buona per preservare al massimo l'aspetto originale del file PDF, ma l'editabilità del documento risultante potrebbe essere limitata. Ogni blocco di testo raggruppato visivamente nel file PDF originale viene convertito in una casella di testo nel documento risultante. Questo garantisce una somiglianza massima del documento di output al file PDF originale. Il documento di output avrà un aspetto gradevole, ma sarà costituito interamente da caselle di testo e potrebbe rendere difficile ulteriori modifiche del documento in Microsoft Word. Questa è la modalità predefinita. |

### IConversionConvertOptions

* class [Enumeration](../../groupdocs.conversion.contracts/enumeration)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
