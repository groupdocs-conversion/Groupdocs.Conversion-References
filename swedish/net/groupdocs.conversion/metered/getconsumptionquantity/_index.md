---
title: "GetConsumptionQuantity"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Hämtar mängden MB som bearbetats."
type: docs
weight: 40
url: /sv/net/groupdocs.conversion/metered/getconsumptionquantity/
---
## Metered.GetConsumptionQuantity method

Hämtar mängden MB som bearbetats.

```csharp
public static decimal GetConsumptionQuantity()
```

### Exempel

Följande exempel visar hur man hämtar mängden MB som bearbetats.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal mbProcessed = Metered.GetConsumptionQuantity();
```

### Se även

* class [Metered](../../metered)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
