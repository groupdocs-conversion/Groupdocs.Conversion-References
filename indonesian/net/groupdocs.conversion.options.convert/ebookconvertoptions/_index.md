---
title: "EBookConvertOptions"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Opsi untuk konversi ke tipe file EBook."
type: docs
weight: 1790
url: /id/net/groupdocs.conversion.options.convert/ebookconvertoptions/
---
## EBookConvertOptions class

Opsi untuk konversi ke tipe file EBook.

```csharp
public class EBookConvertOptions : CommonConvertOptions<EBookFileType>, IPageOrientationOptions, 
    IPageSizeOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [EBookConvertOptions](ebookconvertoptions)() | Menginisialisasi instance baru dari kelas [`EBookConvertOptions`](../ebookconvertoptions). |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [FallbackPageSize](../../groupdocs.conversion.options.convert/ebookconvertoptions/fallbackpagesize) { get; set; } | Ukuran halaman cadangan |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Tipe file yang diinginkan untuk mengonversi dokumen input. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Mengimplementasikan [`Format`](../iconvertoptions/format) |
| [OrientationSettings](../../groupdocs.conversion.options.convert/ebookconvertoptions/orientationsettings) { get; set; } | Pengaturan orientasi halaman |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Mengimplementasikan [`PageNumber`](../ipagedconvertoptions/pagenumber) |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | Menerapkan [`Pages`](../ipagerangedconvertoptions/pages) |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Menerapkan [`PagesCount`](../ipagedconvertoptions/pagescount) |
| [SizeSettings](../../groupdocs.conversion.options.convert/ebookconvertoptions/sizesettings) { get; set; } | Pengaturan ukuran halaman |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Menerapkan [`Watermark`](../iwatermarkedconvertoptions/watermark) |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Menggandakan instance opsi saat ini. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Menentukan apakah dua instance objek sama. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Menentukan apakah dua instance objek sama. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Berfungsi sebagai fungsi hash default. |

### Lihat Juga

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [EBookFileType](../../groupdocs.conversion.filetypes/ebookfiletype)
* interface [IPageOrientationOptions](../../groupdocs.conversion.options/ipageorientationoptions)
* interface [IPageSizeOptions](../../groupdocs.conversion.options/ipagesizeoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
