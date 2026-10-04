---
title: "PdfConvertOptions"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Opsi untuk konversi ke tipe file Pdf."
type: docs
weight: 2060
url: /id/net/groupdocs.conversion.options.convert/pdfconvertoptions/
---
## PdfConvertOptions class

Opsi untuk konversi ke tipe file Pdf.

```csharp
public class PdfConvertOptions : CommonConvertOptions<PdfFileType>, IDpiConvertOptions, 
    IPageMarginOptions, IPageOrientationOptions, IPageSizeOptions, IPasswordConvertOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [PdfConvertOptions](pdfconvertoptions)() | Menginisialisasi instance baru dari kelas [`PdfConvertOptions`](../pdfconvertoptions). |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Dpi](../../groupdocs.conversion.options.convert/pdfconvertoptions/dpi) { get; set; } | DPI halaman yang diinginkan setelah konversi. Resolusi default adalah: 96 dpi. |
| [EmbedFullFonts](../../groupdocs.conversion.options.convert/pdfconvertoptions/embedfullfonts) { get; set; } | Ketika diatur ke true, file font lengkap disematkan ke dalam PDF alih-alih subset. Ini meningkatkan ukuran file output tetapi memastikan kompatibilitas yang lebih baik saat mengedit PDF yang dihasilkan. Hanya berlaku saat mengonversi dari dokumen WordProcessing. |
| [FallbackPageSize](../../groupdocs.conversion.options.convert/pdfconvertoptions/fallbackpagesize) { get; set; } | Ukuran halaman cadangan |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Tipe file yang diinginkan untuk mengonversi dokumen input. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Mengimplementasikan [`Format`](../iconvertoptions/format) |
| [MarginSettings](../../groupdocs.conversion.options.convert/pdfconvertoptions/marginsettings) { get; set; } | Pengaturan margin halaman |
| [OrientationSettings](../../groupdocs.conversion.options.convert/pdfconvertoptions/orientationsettings) { get; set; } | Pengaturan orientasi halaman |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Mengimplementasikan [`PageNumber`](../ipagedconvertoptions/pagenumber) |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | Menerapkan [`Pages`](../ipagerangedconvertoptions/pages) |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Menerapkan [`PagesCount`](../ipagedconvertoptions/pagescount) |
| [Password](../../groupdocs.conversion.options.convert/pdfconvertoptions/password) { get; set; } | Atur properti ini jika Anda ingin melindungi dokumen yang dikonversi dengan kata sandi. |
| [PdfOptions](../../groupdocs.conversion.options.convert/pdfconvertoptions/pdfoptions) { get; set; } | Opsi konversi khusus PDF |
| [ResizeMode](../../groupdocs.conversion.options.convert/pdfconvertoptions/resizemode) { get; set; } | Menentukan bagaimana konten harus diskalakan ketika ukuran halaman diubah. Default adalah AlignTopLeft (tanpa skala). |
| [Rotate](../../groupdocs.conversion.options.convert/pdfconvertoptions/rotate) { get; set; } | Rotasi halaman |
| [SizeSettings](../../groupdocs.conversion.options.convert/pdfconvertoptions/sizesettings) { get; set; } | Pengaturan ukuran halaman |
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
* class [PdfFileType](../../groupdocs.conversion.filetypes/pdffiletype)
* interface [IDpiConvertOptions](../idpiconvertoptions)
* interface [IPageMarginOptions](../../groupdocs.conversion.options/ipagemarginoptions)
* interface [IPageOrientationOptions](../../groupdocs.conversion.options/ipageorientationoptions)
* interface [IPageSizeOptions](../../groupdocs.conversion.options/ipagesizeoptions)
* interface [IPasswordConvertOptions](../ipasswordconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
