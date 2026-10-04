---
title: "PageResizeMode"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Specifica come il contenuto deve essere scalato quando la dimensione della pagina viene modificata"
type: docs
weight: 2050
url: /it/net/groupdocs.conversion.options.convert/pageresizemode/
---
## PageResizeMode class

Specifica come il contenuto deve essere scalato quando la dimensione della pagina viene modificata

```csharp
public sealed class PageResizeMode : Enumeration
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
| static [AlignTopLeft](../../groupdocs.conversion.options.convert/pageresizemode/aligntopleft) | Nessuna scala applicata. Il contenuto è allineato all'angolo in alto a sinistra. |
| static [ScaleToFill](../../groupdocs.conversion.options.convert/pageresizemode/scaletofill) | Allunga il contenuto per riempire l'intera pagina. Può distorcere le proporzioni. |
| static [ScaleToFit](../../groupdocs.conversion.options.convert/pageresizemode/scaletofit) | Scala il contenuto proporzionalmente per adattarlo all'intera pagina senza traboccamento. Può generare spazi bianchi. |
| static [ScaleToHeight](../../groupdocs.conversion.options.convert/pageresizemode/scaletoheight) | Scala il contenuto proporzionalmente per corrispondere all'altezza della pagina. La larghezza può traboccare e essere ritagliata. |
| static [ScaleToWidth](../../groupdocs.conversion.options.convert/pageresizemode/scaletowidth) | Scala il contenuto proporzionalmente per corrispondere alla larghezza della pagina. L'altezza può traboccare e essere ritagliata. |

### IConversionConvertOptions

* class [Enumeration](../../groupdocs.conversion.contracts/enumeration)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
