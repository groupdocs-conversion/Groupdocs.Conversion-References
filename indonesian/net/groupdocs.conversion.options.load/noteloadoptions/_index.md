---
title: "NoteLoadOptions"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Opsi untuk memuat dokumen One."
type: docs
weight: 2680
url: /id/net/groupdocs.conversion.options.load/noteloadoptions/
---
## NoteLoadOptions class

Opsi untuk memuat dokumen One.

```csharp
public sealed class NoteLoadOptions : LoadOptions, IFontSubstituteLoadOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [NoteLoadOptions](noteloadoptions)() | Menginisialisasi instance baru dari kelas [`NoteLoadOptions`](../noteloadoptions). |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [DefaultFont](../../groupdocs.conversion.options.load/noteloadoptions/defaultfont) { get; set; } | Font default untuk dokumen Note. Font berikut akan digunakan jika sebuah font tidak tersedia. |
| [FontSubstitutes](../../groupdocs.conversion.options.load/noteloadoptions/fontsubstitutes) { get; set; } | Mengganti font tertentu saat mengonversi dokumen Note. |
| [Format](../../groupdocs.conversion.options.load/noteloadoptions/format) { get; } | Tipe berkas dokumen input. Nilainya `null` sampai format ditetapkan, jadi periksa apakah `null` daripada membandingkannya dengan [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), yang tidak pernah sama. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Tipe berkas dokumen input. |
| [Password](../../groupdocs.conversion.options.load/noteloadoptions/password) { get; set; } | Atur kata sandi untuk membuka proteksi dokumen yang dilindungi. |

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
