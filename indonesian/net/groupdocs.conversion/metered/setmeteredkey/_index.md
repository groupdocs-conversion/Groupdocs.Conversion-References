---
title: "SetMeteredKey"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Mengaktifkan produk dengan kunci Metered."
type: docs
weight: 20
url: /id/net/groupdocs.conversion/metered/setmeteredkey/
---
## Metered.SetMeteredKey method

Mengaktifkan produk dengan kunci Metered.

```csharp
public void SetMeteredKey(string publicKey, string privateKey)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| publicKey | String | Kunci publik. |
| privateKey | String | Kunci pribadi. |

### Contoh

Contoh berikut menunjukkan cara mengaktifkan produk dengan kunci Metered.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);
```

### Lihat Juga

* class [Metered](../../metered)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
