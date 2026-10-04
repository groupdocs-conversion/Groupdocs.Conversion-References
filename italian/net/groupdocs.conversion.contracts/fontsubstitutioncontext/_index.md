---
title: "FontSubstitutionContext"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Descrive una singola sostituzione di carattere avvenuta durante il caricamento o il rendering di un documento sorgente. Le istanze vengono passate a OnFontSubstituted../groupdocs.conversion/conversionevents/onfontsubstituted."
type: docs
weight: 250
url: /it/net/groupdocs.conversion.contracts/fontsubstitutioncontext/
---
## FontSubstitutionContext class

Descrive una singola sostituzione di carattere avvenuta durante il caricamento o il rendering di un documento sorgente. Le istanze vengono passate a [`OnFontSubstituted`](../../groupdocs.conversion/conversionevents/onfontsubstituted).

```csharp
public sealed class FontSubstitutionContext
```

## Costruttori

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [FontSubstitutionContext](fontsubstitutioncontext)(string, string, string, string) | Crea un nuovo [`FontSubstitutionContext`](../fontsubstitutioncontext). |

## Proprietà

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [OriginalFontName](../../groupdocs.conversion.contracts/fontsubstitutioncontext/originalfontname) { get; } | Nome del carattere a cui fa riferimento il documento sorgente ma non disponibile per la pipeline di conversione. |
| [Reason](../../groupdocs.conversion.contracts/fontsubstitutioncontext/reason) { get; } | Il messaggio di sostituzione esattamente come riportato dalla pipeline di conversione, verbatim e non analizzato. Per i documenti che espongono i nomi dei font in modo strutturale questo può essere `null` (usa [`OriginalFontName`](./originalfontname) / [`SubstituteFontName`](./substitutefontname)); per gli altri contiene la descrizione completa leggibile dall'uomo, che indica sia il font mancante sia quello sostitutivo. |
| [SourceFileName](../../groupdocs.conversion.contracts/fontsubstitutioncontext/sourcefilename) { get; } | Nome file del documento sorgente da convertire. Quando la sorgente è stata fornita come stream che non è un FileStream, questo contiene un identificatore generato anziché un nome file reale. |
| [SubstituteFontName](../../groupdocs.conversion.contracts/fontsubstitutioncontext/substitutefontname) { get; } | Nome del font usato come sostituto. Può essere `null` per i documenti il cui motore segnala la sostituzione solo come testo descrittivo — in tal caso leggi [`Reason`](./reason). |

### IConversionConvertOptions

* namespace [GroupDocs.Conversion.Contracts](../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
