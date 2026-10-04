---
title: "GetConsumptionQuantity"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Recupera la quantità di MB elaborati."
type: docs
weight: 40
url: /it/net/groupdocs.conversion/metered/getconsumptionquantity/
---
## Metered.GetConsumptionQuantity method

Recupera la quantità di MB elaborati.

```csharp
public static decimal GetConsumptionQuantity()
```

### Esempi

L'esempio seguente dimostra come recuperare la quantità di MB elaborati.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal mbProcessed = Metered.GetConsumptionQuantity();
```

### IConversionConvertOptions

* class [Metered](../../metered)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
