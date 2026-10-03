---
title: "GetConsumptionQuantity"
second_title: "GroupDocs.Conversion για .NET Αναφορά API"
description: "Ανακτά το ποσό των επεξεργασμένων MB."
type: docs
weight: 40
url: /el/net/groupdocs.conversion/metered/getconsumptionquantity/
---
## Metered.GetConsumptionQuantity method

Ανακτά το ποσό των επεξεργασμένων MB.

```csharp
public static decimal GetConsumptionQuantity()
```

### Παραδείγματα

Το παρακάτω παράδειγμα δείχνει πώς να ανακτήσετε την ποσότητα των επεξεργασμένων MB.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal mbProcessed = Metered.GetConsumptionQuantity();
```

### Δείτε επίσης

* class [Metered](../../metered)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΙΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.conversion.dll -->
