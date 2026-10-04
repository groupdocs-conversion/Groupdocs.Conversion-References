---
title: "PossibleConversions"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Mewakili pemetaan pasangan konversi yang didukung untuk format file sumber tertentu"
type: docs
weight: 510
url: /id/net/groupdocs.conversion.contracts/possibleconversions/
---
## PossibleConversions class

Mewakili pemetaan pasangan konversi yang didukung untuk format file sumber tertentu

```csharp
public sealed class PossibleConversions : ValueObject
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [All](../../groupdocs.conversion.contracts/possibleconversions/all) { get; } | Semua tipe file target dan flag primary/secondary IEnumerable dari [`TargetConversion`](../targetconversion) |
| [Item](../../groupdocs.conversion.contracts/possibleconversions/item) { get; } | Mengembalikan konversi target untuk tipe file target yang ditentukan (2 indeks) |
| [LoadOptions](../../groupdocs.conversion.contracts/possibleconversions/loadoptions) { get; } | Opsi muat yang telah ditentukan yang dapat digunakan untuk mengonversi dari tipe saat ini |
| [Primary](../../groupdocs.conversion.contracts/possibleconversions/primary) { get; } | Tipe file target utama |
| [Secondary](../../groupdocs.conversion.contracts/possibleconversions/secondary) { get; } | Tipe file target sekunder |
| [Source](../../groupdocs.conversion.contracts/possibleconversions/source) { get; } | Format file sumber |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Menentukan apakah dua instance objek sama. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Menentukan apakah dua instance objek sama. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Berfungsi sebagai fungsi hash default. |

### Lihat Juga

* class [ValueObject](../valueobject)
* namespace [GroupDocs.Conversion.Contracts](../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
