---
title: "OnFontSubstituted"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Generato quando un carattere referenziato dal documento sorgente non è disponibile e viene sostituito o da una regola fornita dal cliente FontSubstitutegroupdocs.conversion.contracts/fontsubstitute, o dal carattere predefinito configurato, o dal fallback interno della pipeline di conversione."
type: docs
weight: 80
url: /it/net/groupdocs.conversion/conversionevents/onfontsubstituted/
---
## ConversionEvents.OnFontSubstituted property

Generato quando un carattere referenziato dal documento sorgente non è disponibile e viene sostituito (o da una regola fornita dal cliente [`FontSubstitute`](../../../groupdocs.conversion.contracts/fontsubstitute), dal carattere predefinito configurato, o dal fallback interno della pipeline di conversione).

```csharp
public Action<FontSubstitutionContext> OnFontSubstituted { get; set; }
```

### Osservazioni

L'evento è deduplicato per `(SourceFileName, OriginalFontName)` all'interno di una singola chiamata `Converter.Convert(...)` — gli iscritti ricevono al massimo una notifica per carattere mancante per documento sorgente. Viene generato in modo sincrono sul thread di conversione. Non viene sollevato per le conversioni di immagini.

Per i documenti di presentazione, la sostituzione dei caratteri viene rilevata solo su Windows, poiché il motore la risolve tramite il matching dei caratteri specifico della piattaforma, non disponibile su altri sistemi operativi.

### IConversionConvertOptions

* class [FontSubstitutionContext](../../../groupdocs.conversion.contracts/fontsubstitutioncontext)
* class [ConversionEvents](../../conversionevents)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
