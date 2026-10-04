---
title: "Elemento"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Restituisce la conversione di destinazione per il tipo di file di destinazione specificato"
type: docs
weight: 20
url: /it/net/groupdocs.conversion.contracts/possibleconversions/item/
---
## PossibleConversions indexer (1 of 2)

Restituisce la conversione di destinazione per il tipo di file di destinazione specificato

```csharp
public TargetConversion this[FileType target] { get; }
```

| Parameter | Descrizione |
| --- | --- |
| destinazione | Il tipo di file per cui ottenere la conversione di destinazione |

### Valore restituito

[`TargetConversion`](../../targetconversion) or null

### IConversionConvertOptions

* class [TargetConversion](../../targetconversion)
* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [PossibleConversions](../../possibleconversions)
* namespace [GroupDocs.Conversion.Contracts](../../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../../)

---

## PossibleConversions indexer (2 of 2)

Restituisce la conversione di destinazione per l'estensione del tipo di file di destinazione specificata

```csharp
public TargetConversion this[string extension] { get; }
```

| Parameter | Descrizione |
| --- | --- |
| estensione | estensione del file per cui restituire la conversione di destinazione |

### Valore restituito

[`TargetConversion`](../../targetconversion) or null

### IConversionConvertOptions

* class [TargetConversion](../../targetconversion)
* class [PossibleConversions](../../possibleconversions)
* namespace [GroupDocs.Conversion.Contracts](../../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
