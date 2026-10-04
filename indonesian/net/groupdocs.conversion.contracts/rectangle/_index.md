---
title: "Persegi panjang"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Mewakili persegi panjang yang didefinisikan oleh tepinya untuk tujuan pemotongan."
type: docs
weight: 580
url: /id/net/groupdocs.conversion.contracts/rectangle/
---
## Rectangle class

Mewakili persegi panjang yang didefinisikan oleh tepinya untuk tujuan pemotongan.

```csharp
public sealed class Rectangle : ValueObject
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [Rectangle](rectangle)(int, int, int, int) | Menginisialisasi instance baru dari struct [`Rectangle`](../rectangle) dengan tepi yang ditentukan. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Bottom](../../groupdocs.conversion.contracts/rectangle/bottom) { get; } | Mendapatkan tepi bawah persegi panjang. |
| [Height](../../groupdocs.conversion.contracts/rectangle/height) { get; } | Mendapatkan tinggi persegi panjang berdasarkan tepi atas dan bawah. |
| [Left](../../groupdocs.conversion.contracts/rectangle/left) { get; } | Mendapatkan tepi kiri persegi panjang. |
| [Right](../../groupdocs.conversion.contracts/rectangle/right) { get; } | Mendapatkan tepi kanan persegi panjang. |
| [Top](../../groupdocs.conversion.contracts/rectangle/top) { get; } | Mendapatkan tepi atas persegi panjang. |
| [Width](../../groupdocs.conversion.contracts/rectangle/width) { get; } | Mendapatkan lebar persegi panjang berdasarkan tepi kiri dan kanan. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Crop](../../groupdocs.conversion.contracts/rectangle/crop)(int, int, int, int) | Membuat versi terpotong dari persegi panjang saat ini dengan menghapus margin yang ditentukan. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Menentukan apakah dua instance objek sama. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Menentukan apakah dua instance objek sama. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Berfungsi sebagai fungsi hash default. |
| override [ToString](../../groupdocs.conversion.contracts/rectangle/tostring)() | Mengembalikan representasi string dari persegi panjang. |

### Lihat Juga

* class [ValueObject](../valueobject)
* namespace [GroupDocs.Conversion.Contracts](../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
