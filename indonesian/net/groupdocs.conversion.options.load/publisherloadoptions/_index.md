---
title: "PublisherLoadOptions"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Opsi untuk memuat dokumen Publisher."
type: docs
weight: 2790
url: /id/net/groupdocs.conversion.options.load/publisherloadoptions/
---
## PublisherLoadOptions class

Opsi untuk memuat dokumen Publisher.

```csharp
public class PublisherLoadOptions : LoadOptions, IFontSubstituteLoadOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [PublisherLoadOptions](publisherloadoptions)() | Menginisialisasi instance baru dari kelas [`PublisherLoadOptions`](../publisherloadoptions). |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [DefaultFont](../../groupdocs.conversion.options.load/publisherloadoptions/defaultfont) { get; set; } | Font default untuk dokumen Publisher. Font berikut akan digunakan jika font tidak tersedia. |
| [FontSubstitutes](../../groupdocs.conversion.options.load/publisherloadoptions/fontsubstitutes) { get; set; } | Ganti font tertentu saat mengonversi dokumen Publisher. |
| [Format](../../groupdocs.conversion.options.load/publisherloadoptions/format) { get; } | Tipe berkas dokumen input. Nilainya `null` sampai format ditetapkan, jadi periksa apakah `null` daripada membandingkannya dengan [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), yang tidak pernah sama. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Tipe berkas dokumen input. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Menentukan apakah dua instance objek sama. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Menentukan apakah dua instance objek sama. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Berfungsi sebagai fungsi hash default. |

### Lihat Juga

* class [LoadOptions](../loadoptions)
* interface [IFontSubstituteLoadOptions](../ifontsubstituteloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
