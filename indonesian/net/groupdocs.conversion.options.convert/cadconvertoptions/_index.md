---
title: "CadConvertOptions"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Opsi untuk konversi ke tipe Cad."
type: docs
weight: 1730
url: /id/net/groupdocs.conversion.options.convert/cadconvertoptions/
---
## CadConvertOptions class

Opsi untuk konversi ke tipe Cad.

```csharp
public class CadConvertOptions : ConvertOptions<CadFileType>, IPagedConvertOptions, IPageSizeOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [CadConvertOptions](cadconvertoptions)() | Menginisialisasi instance baru dari kelas [`CadConvertOptions`](../cadconvertoptions). |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Tipe file yang diinginkan untuk mengonversi dokumen input. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Mengimplementasikan [`Format`](../iconvertoptions/format) |
| [PageNumber](../../groupdocs.conversion.options.convert/cadconvertoptions/pagenumber) { get; set; } | Mengimplementasikan [`PageNumber`](../ipagedconvertoptions/pagenumber) |
| [PagesCount](../../groupdocs.conversion.options.convert/cadconvertoptions/pagescount) { get; set; } | Menerapkan [`PagesCount`](../ipagedconvertoptions/pagescount) |
| [SizeSettings](../../groupdocs.conversion.options.convert/cadconvertoptions/sizesettings) { get; set; } | Pengaturan ukuran halaman |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Menggandakan instance opsi saat ini. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Menentukan apakah dua instance objek sama. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Menentukan apakah dua instance objek sama. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Berfungsi sebagai fungsi hash default. |

### Lihat Juga

* class [ConvertOptions&lt;TFileType&gt;](../convertoptions-1)
* class [CadFileType](../../groupdocs.conversion.filetypes/cadfiletype)
* interface [IPagedConvertOptions](../ipagedconvertoptions)
* interface [IPageSizeOptions](../../groupdocs.conversion.options/ipagesizeoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
