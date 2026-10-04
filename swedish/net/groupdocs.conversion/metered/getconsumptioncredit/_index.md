---
title: "GetConsumptionCredit"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Hämtar antalet förbrukade krediter."
type: docs
weight: 30
url: /sv/net/groupdocs.conversion/metered/getconsumptioncredit/
---
## Metered.GetConsumptionCredit method

Hämtar antalet förbrukade krediter.

```csharp
public static decimal GetConsumptionCredit()
```

### Exempel

Följande exempel visar hur man hämtar antalet förbrukade krediter.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal creditsConsumed = Metered.GetConsumptionCredit();
```

### Se även

* class [Metered](../../metered)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
