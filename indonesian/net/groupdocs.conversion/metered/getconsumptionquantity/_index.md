---
title: GetConsumptionQuantity
second_title: GroupDocs.Konversi untuk Referensi .NET API
description: Mengambil jumlah MB yang diproses.
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

### Lihat juga

* class [Metered](../../metered)
* ruang nama [GroupDocs.Conversion](../../metered)
* perakitan [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->