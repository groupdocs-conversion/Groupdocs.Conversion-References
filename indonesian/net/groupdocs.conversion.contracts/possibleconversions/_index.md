---
title: PossibleConversions
second_title: GroupDocs.Konversi untuk Referensi .NET API
description: Mewakili pemetaan pasangan konversi apa yang didukung untuk format file sumber tertentu
type: docs
weight: 400
url: /id/net/groupdocs.conversion.contracts/possibleconversions/
---
## PossibleConversions class

Mewakili pemetaan pasangan konversi apa yang didukung untuk format file sumber tertentu

```csharp
public sealed class PossibleConversions : ValueObject
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [All](../../groupdocs.conversion.contracts/possibleconversions/all) { get; } | Semua jenis file target dan flag primer/sekunder  IEnumerable of[`TargetConversion`](../targetconversion) |
| [Item](../../groupdocs.conversion.contracts/possibleconversions/item) { get; } | Mengembalikan konversi target untuk jenis file target yang ditentukan (2 indexers) |
| [LoadOptions](../../groupdocs.conversion.contracts/possibleconversions/loadoptions) { get; } | Opsi pemuatan standar yang dapat digunakan untuk mengonversi dari tipe saat ini |
| [Primary](../../groupdocs.conversion.contracts/possibleconversions/primary) { get; } | Jenis file target utama |
| [Secondary](../../groupdocs.conversion.contracts/possibleconversions/secondary) { get; } | Jenis file target sekunder |
| [Source](../../groupdocs.conversion.contracts/possibleconversions/source) { get; } | Format file sumber |

## Metode

| Nama | Keterangan |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Menentukan apakah dua instance objek sama. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Menentukan apakah dua instance objek sama. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Berfungsi sebagai fungsi hash default. |

### Lihat juga

* class [ValueObject](../valueobject)
* ruang nama [GroupDocs.Conversion.Contracts](../../groupdocs.conversion.contracts)
* perakitan [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->