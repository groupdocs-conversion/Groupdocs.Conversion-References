---
title: "GetConsumptionCredit"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Ανακτά τον αριθμό των καταναλωμένων πόντων."
type: docs
weight: 30
url: /el/net/groupdocs.conversion/metered/getconsumptioncredit/
---
## Metered.GetConsumptionCredit method

Ανακτά τον αριθμό των καταναλωμένων πόντων.

```csharp
public static decimal GetConsumptionCredit()
```

### Παραδείγματα

Το παρακάτω παράδειγμα δείχνει πώς να ανακτήσετε τον αριθμό των καταναλωμένων πιστώσεων.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal creditsConsumed = Metered.GetConsumptionCredit();
```

### Δείτε επίσης

* class [Metered](../../metered)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
