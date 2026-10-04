---
title: "OlmLoadOptions"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Opzioni per il caricamento di documenti Olm."
type: docs
weight: 2700
url: /it/net/groupdocs.conversion.options.load/olmloadoptions/
---
## OlmLoadOptions class

Opzioni per il caricamento di documenti Olm.

```csharp
public sealed class OlmLoadOptions : LoadOptions, IDocumentsContainerLoadOptions
```

## Costruttori

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [OlmLoadOptions](olmloadoptions)() | Inizializza una nuova istanza della classe [`OlmLoadOptions`](../olmloadoptions). |

## Proprietà

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [ConvertOwned](../../groupdocs.conversion.options.load/olmloadoptions/convertowned) { get; } | Implementa [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) in sola lettura. Impostato su true. I documenti di proprietà saranno convertiti. |
| [ConvertOwner](../../groupdocs.conversion.options.load/olmloadoptions/convertowner) { get; } | Implementa [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) in sola lettura. Impostato su false. Il proprietario non sarà convertito. |
| [Depth](../../groupdocs.conversion.options.load/olmloadoptions/depth) { get; set; } | Implementa [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth) Predefinito: 3 |
| [Folder](../../groupdocs.conversion.options.load/olmloadoptions/folder) { get; set; } | Cartella da elaborare. Il valore predefinito è Inbox. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Tipo di file del documento di input. |

## Vedi anche

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.load/olmloadoptions/clone)() | Clona l'istanza corrente. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina se due istanze di oggetti sono uguali. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina se due istanze di oggetti sono uguali. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Funziona come funzione hash predefinita. |

### IConversionConvertOptions

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
