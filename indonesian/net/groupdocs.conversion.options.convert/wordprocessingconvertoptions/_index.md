---
title: "WordProcessingConvertOptions"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Opsi untuk konversi ke tipe file Pengolah Kata."
type: docs
weight: 2340
url: /id/net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/
---
## WordProcessingConvertOptions class

Opsi untuk konversi ke tipe file Pengolah Kata.

```csharp
public class WordProcessingConvertOptions : CommonConvertOptions<WordProcessingFileType>, 
    IDpiConvertOptions, IPageMarginOptions, IPageOrientationOptions, IPageSizeOptions, 
    IPasswordConvertOptions, IPdfRecognitionModeOptions, IZoomConvertOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [WordProcessingConvertOptions](wordprocessingconvertoptions)() | Menginisialisasi instance baru dari kelas [`WordProcessingConvertOptions`](../wordprocessingconvertoptions). |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Dpi](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/dpi) { get; set; } | DPI halaman yang diinginkan setelah konversi. Resolusi default adalah: 96 dpi. |
| [FallbackPageSize](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/fallbackpagesize) { get; set; } | Ukuran halaman cadangan |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Tipe file yang diinginkan untuk mengonversi dokumen input. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Mengimplementasikan [`Format`](../iconvertoptions/format) |
| [MarginSettings](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/marginsettings) { get; set; } | Pengaturan margin halaman |
| [MarkdownOptions](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/markdownoptions) { get; set; } | Mengimplementasikan [`MarkdownOptions`](./markdownoptions) |
| [OrientationSettings](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/orientationsettings) { get; set; } | Pengaturan orientasi halaman |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Mengimplementasikan [`PageNumber`](../ipagedconvertoptions/pagenumber) |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | Menerapkan [`Pages`](../ipagerangedconvertoptions/pages) |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Menerapkan [`PagesCount`](../ipagedconvertoptions/pagescount) |
| [Password](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/password) { get; set; } | Atur properti ini jika Anda ingin melindungi dokumen yang dikonversi dengan kata sandi. |
| [PdfRecognitionMode](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/pdfrecognitionmode) { get; set; } | Mengimplementasikan [`PdfRecognitionMode`](../ipdfrecognitionmodeoptions/pdfrecognitionmode) |
| [RtfOptions](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/rtfoptions) { get; set; } | Opsi konversi khusus RTF |
| [SizeSettings](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/sizesettings) { get; set; } | Pengaturan ukuran halaman |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Menerapkan [`Watermark`](../iwatermarkedconvertoptions/watermark) |
| [Zoom](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/zoom) { get; set; } | Menentukan tingkat zoom dalam persentase. Default adalah 100. Zoom default didukung hingga Microsoft Word 2010. Mulai dari Microsoft Word 2013, zoom default tidak lagi diatur ke dokumen, melainkan tampaknya menggunakan faktor zoom dari dokumen terakhir yang dibuka. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Menggandakan instance opsi saat ini. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Menentukan apakah dua instance objek sama. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Menentukan apakah dua instance objek sama. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Berfungsi sebagai fungsi hash default. |

### Lihat Juga

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [WordProcessingFileType](../../groupdocs.conversion.filetypes/wordprocessingfiletype)
* interface [IDpiConvertOptions](../idpiconvertoptions)
* interface [IPageMarginOptions](../../groupdocs.conversion.options/ipagemarginoptions)
* interface [IPageOrientationOptions](../../groupdocs.conversion.options/ipageorientationoptions)
* interface [IPageSizeOptions](../../groupdocs.conversion.options/ipagesizeoptions)
* interface [IPasswordConvertOptions](../ipasswordconvertoptions)
* interface [IPdfRecognitionModeOptions](../ipdfrecognitionmodeoptions)
* interface [IZoomConvertOptions](../izoomconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
