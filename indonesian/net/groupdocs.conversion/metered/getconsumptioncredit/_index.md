---
title: "GetConsumptionCredit"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Mengambil jumlah kredit yang digunakan."
type: docs
weight: 30
url: /id/net/groupdocs.conversion/metered/getconsumptioncredit/
---
## Metered.GetConsumptionCredit method

Mengambil jumlah kredit yang digunakan.

```csharp
public static decimal GetConsumptionCredit()
```

### Contoh

Contoh berikut menunjukkan cara mengambil jumlah kredit yang digunakan.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal creditsConsumed = Metered.GetConsumptionCredit();
```

### Lihat Juga

* class [Metered](../../metered)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
