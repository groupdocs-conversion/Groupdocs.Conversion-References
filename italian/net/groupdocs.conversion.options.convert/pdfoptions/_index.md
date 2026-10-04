---
title: "PdfOptions"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Opzioni per la conversione al tipo di file Pdf."
type: docs
weight: 2130
url: /it/net/groupdocs.conversion.options.convert/pdfoptions/
---
## PdfOptions class

Opzioni per la conversione al tipo di file Pdf.

```csharp
public sealed class PdfOptions : ValueObject, IZoomConvertOptions
```

## Costruttori

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [PdfOptions](pdfoptions)() | Inizializza una nuova istanza della classe [`PdfOptions`](../pdfoptions). |

## Proprietà

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [DocumentInfo](../../groupdocs.conversion.options.convert/pdfoptions/documentinfo) { get; set; } | Metainformazioni del documento PDF. |
| [FormattingOptions](../../groupdocs.conversion.options.convert/pdfoptions/formattingoptions) { get; set; } | Opzioni di formattazione PDF |
| [Grayscale](../../groupdocs.conversion.options.convert/pdfoptions/grayscale) { get; set; } | Converti un PDF dallo spazio colore RGB a scala di grigi |
| [Linearize](../../groupdocs.conversion.options.convert/pdfoptions/linearize) { get; set; } | Linearizza il documento PDF per il Web |
| [OptimizationOptions](../../groupdocs.conversion.options.convert/pdfoptions/optimizationoptions) { get; set; } | Opzioni di ottimizzazione PDF |
| [PdfFormat](../../groupdocs.conversion.options.convert/pdfoptions/pdfformat) { get; set; } | Imposta il formato PDF del documento convertito. |
| [RemovePdfACompliance](../../groupdocs.conversion.options.convert/pdfoptions/removepdfacompliance) { get; set; } | Rimuove la conformità PDF/A |
| [Zoom](../../groupdocs.conversion.options.convert/pdfoptions/zoom) { get; set; } | Specifica il livello di zoom in percentuale. Il valore predefinito è 100. |

## Vedi anche

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina se due istanze di oggetti sono uguali. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina se due istanze di oggetti sono uguali. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Funziona come funzione hash predefinita. |

### IConversionConvertOptions

* class [ValueObject](../../groupdocs.conversion.contracts/valueobject)
* interface [IZoomConvertOptions](../izoomconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
