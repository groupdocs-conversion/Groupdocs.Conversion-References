---
title: "GetConsumptionCredit"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Récupère le nombre de crédits consommés."
type: docs
weight: 30
url: /fr/net/groupdocs.conversion/metered/getconsumptioncredit/
---
## Metered.GetConsumptionCredit method

Récupère le nombre de crédits consommés.

```csharp
public static decimal GetConsumptionCredit()
```

### Exemples

L'exemple suivant montre comment récupérer le nombre de crédits consommés.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal creditsConsumed = Metered.GetConsumptionCredit();
```

### Voir aussi

* class [Metered](../../metered)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
