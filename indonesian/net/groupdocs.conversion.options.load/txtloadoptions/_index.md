---
title: "TxtLoadOptions"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Opsi untuk memuat dokumen Txt."
type: docs
weight: 2870
url: /id/net/groupdocs.conversion.options.load/txtloadoptions/
---
## TxtLoadOptions class

Opsi untuk memuat dokumen Txt.

```csharp
public sealed class TxtLoadOptions : LoadOptions, IPageMarginOptions, IPageSizeOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [TxtLoadOptions](txtloadoptions)() | Menginisialisasi instance baru dari kelas [`TxtLoadOptions`](../txtloadoptions). |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [DefaultFont](../../groupdocs.conversion.options.load/txtloadoptions/defaultfont) { get; set; } | Font yang digunakan saat merender konten teks biasa selama konversi. Karena file TXT tidak mengandung informasi font, properti ini menentukan font tampilan untuk konten teks. Default: Arial 10pt. |
| [DetectNumberingWithWhitespaces](../../groupdocs.conversion.options.load/txtloadoptions/detectnumberingwithwhitespaces) { get; set; } | Memungkinkan untuk menentukan bagaimana item daftar bernomor dikenali saat dokumen teks biasa dikonversi. Nilai default adalah true. |
| [Encoding](../../groupdocs.conversion.options.load/txtloadoptions/encoding) { get; set; } | Mendapatkan atau mengatur enkoding yang akan digunakan saat memuat dokumen Txt. Bisa bernilai null. Default adalah null. |
| [Format](../../groupdocs.conversion.options.load/txtloadoptions/format) { get; } | Tipe berkas dokumen input. Nilainya `null` sampai format ditetapkan, jadi periksa apakah `null` daripada membandingkannya dengan [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), yang tidak pernah sama. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Tipe berkas dokumen input. |
| [LeadingSpacesOptions](../../groupdocs.conversion.options.load/txtloadoptions/leadingspacesoptions) { get; set; } | Mendapatkan atau mengatur opsi preferensi penanganan spasi di awal. Nilai default adalah [`ConvertToIndent`](../txtleadingspacesoptions/converttoindent). |
| [MarginSettings](../../groupdocs.conversion.options.load/txtloadoptions/marginsettings) { get; set; } | Pengaturan margin halaman |
| [SizeSettings](../../groupdocs.conversion.options.load/txtloadoptions/sizesettings) { get; set; } | Pengaturan ukuran halaman |
| [TrailingSpacesOptions](../../groupdocs.conversion.options.load/txtloadoptions/trailingspacesoptions) { get; set; } | Mendapatkan atau mengatur opsi preferensi penanganan spasi di akhir. Nilai default adalah [`Trim`](../txttrailingspacesoptions/trim). |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Menentukan apakah dua instance objek sama. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Menentukan apakah dua instance objek sama. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Berfungsi sebagai fungsi hash default. |

### Catatan

**Font Configuration for Plain Text:**

Karena file TXT tidak mengandung informasi font, gunakan DefaultTextFont untuk menentukan

font untuk merender konten teks biasa selama konversi.

### Lihat Juga

* class [LoadOptions](../loadoptions)
* interface [IPageMarginOptions](../../groupdocs.conversion.options/ipagemarginoptions)
* interface [IPageSizeOptions](../../groupdocs.conversion.options/ipagesizeoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
