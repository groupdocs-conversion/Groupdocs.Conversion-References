---
title: "SpreadsheetConvertOptions"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Opsi untuk konversi ke tipe file Spreadsheet."
type: docs
weight: 2240
url: /id/net/groupdocs.conversion.options.convert/spreadsheetconvertoptions/
---
## SpreadsheetConvertOptions class

Opsi untuk konversi ke tipe file Spreadsheet.

```csharp
public class SpreadsheetConvertOptions : CommonConvertOptions<SpreadsheetFileType>, 
    IPasswordConvertOptions, IZoomConvertOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [SpreadsheetConvertOptions](spreadsheetconvertoptions)() | Menginisialisasi instance baru dari kelas [`SpreadsheetConvertOptions`](../spreadsheetconvertoptions). |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Encoding](../../groupdocs.conversion.options.convert/spreadsheetconvertoptions/encoding) { get; set; } | Menentukan enkoding yang akan digunakan saat mengonversi ke format terdelimit. |
| [Format](../../groupdocs.conversion.options.convert/spreadsheetconvertoptions/format) { get; set; } | Jenis file yang diinginkan untuk mengonversi dokumen masukan. (2 properti) |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Mengimplementasikan [`Format`](../iconvertoptions/format) |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Mengimplementasikan [`PageNumber`](../ipagedconvertoptions/pagenumber) |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | Menerapkan [`Pages`](../ipagerangedconvertoptions/pages) |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Menerapkan [`PagesCount`](../ipagedconvertoptions/pagescount) |
| [Password](../../groupdocs.conversion.options.convert/spreadsheetconvertoptions/password) { get; set; } | Atur properti ini jika Anda ingin melindungi dokumen yang dikonversi dengan kata sandi. |
| [Separator](../../groupdocs.conversion.options.convert/spreadsheetconvertoptions/separator) { get; set; } | Menentukan pemisah yang akan digunakan saat mengonversi ke format terdelimit. |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Menerapkan [`Watermark`](../iwatermarkedconvertoptions/watermark) |
| [Zoom](../../groupdocs.conversion.options.convert/spreadsheetconvertoptions/zoom) { get; set; } | Menentukan tingkat zoom dalam persentase. Defaultnya 100. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Menggandakan instance opsi saat ini. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Menentukan apakah dua instance objek sama. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Menentukan apakah dua instance objek sama. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Berfungsi sebagai fungsi hash default. |

### Lihat Juga

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [SpreadsheetFileType](../../groupdocs.conversion.filetypes/spreadsheetfiletype)
* interface [IPasswordConvertOptions](../ipasswordconvertoptions)
* interface [IZoomConvertOptions](../izoomconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
