---
title: "PclLoadOptions"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Opzioni per il caricamento di documenti Pcl."
type: docs
weight: 2730
url: /it/net/groupdocs.conversion.options.load/pclloadoptions/
---
## PclLoadOptions class

Opzioni per il caricamento di documenti Pcl.

```csharp
public sealed class PclLoadOptions : LoadOptions
```

## Costruttori

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [PclLoadOptions](pclloadoptions)() | Inizializza una nuova istanza della classe [`PclLoadOptions`](../pclloadoptions). |

## Proprietà

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [Format](../../groupdocs.conversion.options.load/pclloadoptions/format) { get; } | Tipo di file del documento di input. È `null` finché non è stato impostato un formato, quindi testalo per `null` anziché contro [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), a cui non è mai uguale. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Tipo di file del documento di input. |
| [ResetFontFolders](../../groupdocs.conversion.options.load/pclloadoptions/resetfontfolders) { get; set; } | Reimposta le cartelle dei caratteri prima di caricare il documento |

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
