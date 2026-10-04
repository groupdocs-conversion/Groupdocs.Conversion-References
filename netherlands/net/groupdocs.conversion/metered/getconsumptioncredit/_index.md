---
title: "GetConsumptionCredit"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Haalt het aantal verbruikte credits op."
type: docs
weight: 30
url: /nl/net/groupdocs.conversion/metered/getconsumptioncredit/
---
## Metered.GetConsumptionCredit method

Haalt het aantal verbruikte credits op.

```csharp
public static decimal GetConsumptionCredit()
```

### Voorbeelden

Het volgende voorbeeld toont hoe het aantal verbruikte credits op te halen.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal creditsConsumed = Metered.GetConsumptionCredit();
```

### Zie ook

* class [Metered](../../metered)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
