---
title: "PersonalStorageLoadOptions"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Opzioni per il caricamento di documenti personal storage."
type: docs
weight: 2750
url: /it/net/groupdocs.conversion.options.load/personalstorageloadoptions/
---
## PersonalStorageLoadOptions class

Opzioni per il caricamento di documenti personal storage.

```csharp
public sealed class PersonalStorageLoadOptions : LoadOptions, IDocumentsContainerLoadOptions
```

## Costruttori

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [PersonalStorageLoadOptions](personalstorageloadoptions)() | Inizializza una nuova istanza della classe [`PersonalStorageLoadOptions`](../personalstorageloadoptions). |

## Proprietà

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [ConvertOwned](../../groupdocs.conversion.options.load/personalstorageloadoptions/convertowned) { get; } | Implementa [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) in sola lettura. Impostato su true. I documenti di proprietà saranno convertiti. |
| [ConvertOwner](../../groupdocs.conversion.options.load/personalstorageloadoptions/convertowner) { get; } | Implementa [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) in sola lettura. Impostato su false. Il proprietario non sarà convertito. |
| [Depth](../../groupdocs.conversion.options.load/personalstorageloadoptions/depth) { get; set; } | Implementa [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth) Predefinito: 3 |
| [Folder](../../groupdocs.conversion.options.load/personalstorageloadoptions/folder) { get; set; } | Cartella da elaborare. Il valore predefinito è Inbox. |
| [Format](../../groupdocs.conversion.options.load/personalstorageloadoptions/format) { get; set; } | Tipo di file del documento di input. È `null` finché non è stato impostato un formato, quindi testalo per `null` anziché contro [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), a cui non è mai uguale. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Tipo di file del documento di input. |

## Vedi anche

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.load/personalstorageloadoptions/clone)() | Clona l'istanza corrente. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina se due istanze di oggetti sono uguali. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina se due istanze di oggetti sono uguali. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Funziona come funzione hash predefinita. |

### IConversionConvertOptions

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
