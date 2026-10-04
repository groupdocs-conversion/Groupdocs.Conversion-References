---
title: "GetConsumptionCredit"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Recupera il conteggio dei crediti consumati."
type: docs
weight: 30
url: /it/net/groupdocs.conversion/metered/getconsumptioncredit/
---
## Metered.GetConsumptionCredit method

Recupera il conteggio dei crediti consumati.

```csharp
public static decimal GetConsumptionCredit()
```

### Esempi

L'esempio seguente dimostra come recuperare il conteggio dei crediti consumati.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal creditsConsumed = Metered.GetConsumptionCredit();
```

### IConversionConvertOptions

* class [Metered](../../metered)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
