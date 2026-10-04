---
title: "PossibleConversions"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Rappresenta una mappatura delle coppie di conversione supportate per un formato di file sorgente specifico"
type: docs
weight: 510
url: /it/net/groupdocs.conversion.contracts/possibleconversions/
---
## PossibleConversions class

Rappresenta una mappatura delle coppie di conversione supportate per un formato di file sorgente specifico

```csharp
public sealed class PossibleConversions : ValueObject
```

## Proprietà

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [All](../../groupdocs.conversion.contracts/possibleconversions/all) { get; } | Tutti i tipi di file di destinazione e il flag primario/secondario IEnumerable di [`TargetConversion`](../targetconversion) |
| [Item](../../groupdocs.conversion.contracts/possibleconversions/item) { get; } | Restituisce la conversione di destinazione per il tipo di file di destinazione specificato (2 indicizzatori) |
| [LoadOptions](../../groupdocs.conversion.contracts/possibleconversions/loadoptions) { get; } | Opzioni di caricamento predefinite che possono essere utilizzate per convertire dal tipo corrente |
| [Primary](../../groupdocs.conversion.contracts/possibleconversions/primary) { get; } | Tipi di file di destinazione primari |
| [Secondary](../../groupdocs.conversion.contracts/possibleconversions/secondary) { get; } | Tipi di file di destinazione secondari |
| [Source](../../groupdocs.conversion.contracts/possibleconversions/source) { get; } | Formati di file sorgente |

## Vedi anche

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina se due istanze di oggetti sono uguali. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina se due istanze di oggetti sono uguali. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Funziona come funzione hash predefinita. |

### IConversionConvertOptions

* class [ValueObject](../valueobject)
* namespace [GroupDocs.Conversion.Contracts](../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
