---
title: "MboxLoadOptions"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Opzioni per il caricamento di documenti Mbox."
type: docs
weight: 2670
url: /it/net/groupdocs.conversion.options.load/mboxloadoptions/
---
## MboxLoadOptions class

Opzioni per il caricamento di documenti Mbox.

```csharp
public sealed class MboxLoadOptions : LoadOptions, IDocumentsContainerLoadOptions
```

## Costruttori

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [MboxLoadOptions](mboxloadoptions)() | Inizializza una nuova istanza della classe [`MboxLoadOptions`](../mboxloadoptions). |

## Proprietà

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [ConvertOwned](../../groupdocs.conversion.options.load/mboxloadoptions/convertowned) { get; } | Implementa [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) in sola lettura. Impostato su true. I documenti di proprietà saranno convertiti. |
| [ConvertOwner](../../groupdocs.conversion.options.load/mboxloadoptions/convertowner) { get; } | Implementa [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) in sola lettura. Impostato su false. Il proprietario non sarà convertito. |
| [Depth](../../groupdocs.conversion.options.load/mboxloadoptions/depth) { get; set; } | Implementa [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth) Predefinito: 3 |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Tipo di file del documento di input. |

## Vedi anche

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.load/mboxloadoptions/clone)() | Clona l'istanza corrente. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina se due istanze di oggetti sono uguali. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina se due istanze di oggetti sono uguali. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Funziona come funzione hash predefinita. |

### IConversionConvertOptions

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
