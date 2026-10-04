---
title: "CompressionLoadOptions"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Opzioni per il caricamento di documenti compressi."
type: docs
weight: 2440
url: /it/net/groupdocs.conversion.options.load/compressionloadoptions/
---
## CompressionLoadOptions class

Opzioni per il caricamento di documenti compressi.

```csharp
public sealed class CompressionLoadOptions : LoadOptions, IDocumentsContainerLoadOptions
```

## Costruttori

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [CompressionLoadOptions](compressionloadoptions)() | Inizializza una nuova istanza della classe [`CompressionLoadOptions`](../compressionloadoptions). |

## Proprietà

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [ConvertOwned](../../groupdocs.conversion.options.load/compressionloadoptions/convertowned) { get; } | Implementa [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) in sola lettura. Impostato su true. I documenti di proprietà saranno convertiti. |
| [ConvertOwner](../../groupdocs.conversion.options.load/compressionloadoptions/convertowner) { get; } | Implementa [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) in sola lettura. Impostato su false. Il proprietario non sarà convertito. |
| [Depth](../../groupdocs.conversion.options.load/compressionloadoptions/depth) { get; set; } | Implementa [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth) Predefinito: 3 |
| [Format](../../groupdocs.conversion.options.load/compressionloadoptions/format) { get; set; } | Tipo di file del documento di input. È `null` finché non è stato impostato un formato, quindi testalo per `null` anziché contro [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), a cui non è mai uguale. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Tipo di file del documento di input. |
| [Password](../../groupdocs.conversion.options.load/compressionloadoptions/password) { get; set; } | Imposta la password per caricare il documento protetto. |

## Vedi anche

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina se due istanze di oggetti sono uguali. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina se due istanze di oggetti sono uguali. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Funziona come funzione hash predefinita. |

### IConversionConvertOptions

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
