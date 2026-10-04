---
title: "BaseImageLoadOptions"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Opsi untuk memuat dokumen Gambar."
type: docs
weight: 2400
url: /id/net/groupdocs.conversion.options.load/baseimageloadoptions/
---
## BaseImageLoadOptions class

Opsi untuk memuat dokumen Gambar.

```csharp
public abstract class BaseImageLoadOptions : LoadOptions
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [DefaultFont](../../groupdocs.conversion.options.load/baseimageloadoptions/defaultfont) { get; set; } | Font default untuk tipe dokumen Psd, Emf, Wmf. Font berikut akan digunakan jika font tidak tersedia. |
| [Format](../../groupdocs.conversion.options.load/baseimageloadoptions/format) { get; set; } | Tipe berkas dokumen input. Nilainya `null` sampai format ditetapkan, jadi periksa apakah `null` daripada membandingkannya dengan [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), yang tidak pernah sama. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Tipe berkas dokumen input. |
| [ResetFontFolders](../../groupdocs.conversion.options.load/baseimageloadoptions/resetfontfolders) { get; set; } | Atur ulang folder font sebelum memuat dokumen |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Menentukan apakah dua instance objek sama. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Menentukan apakah dua instance objek sama. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Berfungsi sebagai fungsi hash default. |

### Lihat Juga

* class [LoadOptions](../loadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
