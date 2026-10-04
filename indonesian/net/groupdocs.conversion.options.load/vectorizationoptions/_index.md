---
title: "VectorizationOptions"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Opsi untuk vektorisasi gambar."
type: docs
weight: 2900
url: /id/net/groupdocs.conversion.options.load/vectorizationoptions/
---
## VectorizationOptions class

Opsi untuk vektorisasi gambar.

```csharp
public class VectorizationOptions : ValueObject
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [VectorizationOptions](vectorizationoptions)() | Konstruktor default untuk VectorizationOptions. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [BackgroundColor](../../groupdocs.conversion.options.load/vectorizationoptions/backgroundcolor) { get; set; } | Mendapatkan atau mengatur warna latar belakang. Nilai default adalah putih transparan. |
| [ColorsLimit](../../groupdocs.conversion.options.load/vectorizationoptions/colorslimit) { get; set; } | Mendapatkan atau mengatur jumlah maksimum warna yang digunakan untuk mengkuantisasi gambar. Nilai default adalah 25. |
| [EnableVectorization](../../groupdocs.conversion.options.load/vectorizationoptions/enablevectorization) { get; set; } | Aktifkan vektorisasi gambar. Default adalah false. |
| [ImageSizeLimit](../../groupdocs.conversion.options.load/vectorizationoptions/imagesizelimit) { get; set; } | Mendapatkan atau mengatur dimensi maksimal gambar yang ditentukan oleh perkalian lebar dan tinggi gambar. Ukuran gambar akan diubah skalanya berdasarkan properti ini. Nilai default adalah 1800000. |
| [LineWidth](../../groupdocs.conversion.options.load/vectorizationoptions/linewidth) { get; set; } | Mendapatkan atau mengatur lebar garis. Nilai parameter ini dipengaruhi oleh skala grafik. Nilai default adalah 1. |
| [Severity](../../groupdocs.conversion.options.load/vectorizationoptions/severity) { get; set; } | Mengatur tingkat keparahan pelicinan jejak gambar |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Menentukan apakah dua instance objek sama. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Menentukan apakah dua instance objek sama. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Berfungsi sebagai fungsi hash default. |

### Lihat Juga

* class [ValueObject](../../groupdocs.conversion.contracts/valueobject)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
