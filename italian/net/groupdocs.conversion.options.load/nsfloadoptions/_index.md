---
title: "NsfLoadOptions"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Opzioni per il caricamento di documenti Nsf."
type: docs
weight: 2690
url: /it/net/groupdocs.conversion.options.load/nsfloadoptions/
---
## NsfLoadOptions class

Opzioni per il caricamento di documenti Nsf.

```csharp
public sealed class NsfLoadOptions : LoadOptions, IDocumentsContainerLoadOptions
```

## Costruttori

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [NsfLoadOptions](nsfloadoptions)() | Inizializza una nuova istanza della classe [`NsfLoadOptions`](../nsfloadoptions). |

## Proprietà

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [ConvertOwned](../../groupdocs.conversion.options.load/nsfloadoptions/convertowned) { get; } | Implementa [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) in sola lettura. Impostato su true. I documenti di proprietà saranno convertiti. |
| [ConvertOwner](../../groupdocs.conversion.options.load/nsfloadoptions/convertowner) { get; } | Implementa [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) in sola lettura. Impostato su false. Il proprietario non sarà convertito. |
| [Depth](../../groupdocs.conversion.options.load/nsfloadoptions/depth) { get; set; } | Implementa [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth) Predefinito: 3 |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Tipo di file del documento di input. |

## Vedi anche

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.load/nsfloadoptions/clone)() | Clona l'istanza corrente. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina se due istanze di oggetti sono uguali. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina se due istanze di oggetti sono uguali. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Funziona come funzione hash predefinita. |

### IConversionConvertOptions

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
