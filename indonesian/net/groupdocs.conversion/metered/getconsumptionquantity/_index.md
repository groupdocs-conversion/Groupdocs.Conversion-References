---
title: "GetConsumptionQuantity"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Mengambil jumlah MB yang diproses."
type: docs
weight: 40
url: /id/net/groupdocs.conversion/metered/getconsumptionquantity/
---
## Metered.GetConsumptionQuantity method

Mengambil jumlah MB yang diproses.

```csharp
public static decimal GetConsumptionQuantity()
```

### Contoh

Contoh berikut menunjukkan cara mengambil jumlah MB yang diproses.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal mbProcessed = Metered.GetConsumptionQuantity();
```

### Lihat Juga

* class [Metered](../../metered)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
