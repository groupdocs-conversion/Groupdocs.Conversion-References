---
title: "PdfOptimizationOptions"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Definisce le opzioni di ottimizzazione Pdf."
type: docs
weight: 2120
url: /it/net/groupdocs.conversion.options.convert/pdfoptimizationoptions/
---
## PdfOptimizationOptions class

Definisce le opzioni di ottimizzazione Pdf.

```csharp
public sealed class PdfOptimizationOptions : ValueObject
```

## Costruttori

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [PdfOptimizationOptions](pdfoptimizationoptions)() | Inizializza una nuova istanza della classe [`PdfOptimizationOptions`](../pdfoptimizationoptions). |

## Proprietà

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [CompressImages](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/compressimages) { get; set; } | Se CompressImages è impostato su `true`, tutte le immagini nel documento vengono ricomprese. La compressione è definita dalla proprietà ImageQuality. |
| [FontSubsetStrategy](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/fontsubsetstrategy) { get; set; } | Imposta la strategia di sottoinsieme dei font |
| [ImageQuality](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/imagequality) { get; set; } | Valore in percentuale dove 100% corrisponde a qualità e dimensione dell'immagine invariata. Per ridurre la dimensione dell'immagine impostare questa proprietà a meno di 100 |
| [LinkDuplicateStreams](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/linkduplicatestreams) { get; set; } | Collega i flussi duplicati |
| [RemoveUnusedObjects](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/removeunusedobjects) { get; set; } | Rimuovi gli oggetti inutilizzati |
| [RemoveUnusedStreams](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/removeunusedstreams) { get; set; } | Rimuovi i flussi inutilizzati |
| [UnembedFonts](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/unembedfonts) { get; set; } | Rendi i font non incorporati se impostato su true |

## Vedi anche

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina se due istanze di oggetti sono uguali. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina se due istanze di oggetti sono uguali. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Funziona come funzione hash predefinita. |

### IConversionConvertOptions

* class [ValueObject](../../groupdocs.conversion.contracts/valueobject)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
