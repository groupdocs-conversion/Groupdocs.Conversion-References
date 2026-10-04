---
title: "GisLoadOptions"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Opzioni per il caricamento di documenti GIS."
type: docs
weight: 2540
url: /it/net/groupdocs.conversion.options.load/gisloadoptions/
---
## GisLoadOptions class

Opzioni per il caricamento di documenti GIS.

```csharp
public class GisLoadOptions : LoadOptions
```

## Costruttori

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [GisLoadOptions](gisloadoptions)() | Inizializza una nuova istanza della classe [`GisLoadOptions`](../gisloadoptions). |

## Proprietà

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [Format](../../groupdocs.conversion.options.load/gisloadoptions/format) { get; set; } | Tipo di file del documento di input. È `null` finché non è stato impostato un formato, quindi testalo per `null` anziché contro [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), a cui non è mai uguale. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Tipo di file del documento di input. |
| [Height](../../groupdocs.conversion.options.load/gisloadoptions/height) { get; set; } | Imposta l'altezza della pagina desiderata per la conversione del documento GIS. Il valore predefinito è 1000. |
| [Width](../../groupdocs.conversion.options.load/gisloadoptions/width) { get; set; } | Imposta la larghezza della pagina desiderata per la conversione del documento GIS. Il valore predefinito è 1000. |

## Vedi anche

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina se due istanze di oggetti sono uguali. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina se due istanze di oggetti sono uguali. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Funziona come funzione hash predefinita. |

### IConversionConvertOptions

* class [LoadOptions](../loadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
