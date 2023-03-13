---
title: WordProcessingConvertOptions
second_title: GroupDocs.Konversi untuk Referensi .NET API
description: Opsi untuk konversi ke jenis file Pemrosesan Kata.
type: docs
weight: 2000
url: /id/net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/
---
## WordProcessingConvertOptions class

Opsi untuk konversi ke jenis file Pemrosesan Kata.

```csharp
public class WordProcessingConvertOptions : CommonConvertOptions<WordProcessingFileType>, 
    IPageMarginConvertOptions, IPageOrientationConvertOptions, IPageSizeConvertOptions, 
    IPdfRecognitionModeOptions
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [WordProcessingConvertOptions](wordprocessingconvertoptions)() | Menginisialisasi instance baru[`WordProcessingConvertOptions`](../wordprocessingconvertoptions) kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [Dpi](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/dpi) { get; set; } | DPI halaman yang diinginkan setelah konversi. Resolusi default adalah: 96 dpi. |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Jenis file yang diinginkan untuk konversi dokumen masukan. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Jenis file yang diinginkan untuk konversi dokumen masukan. |
| [Height](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/height) { get; set; } | Tinggi halaman yang diinginkan setelah konversi. |
| [MarginBottom](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/marginbottom) { get; set; } | Margin bawah halaman yang diinginkan dalam piksel setelah konversi. |
| [MarginLeft](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/marginleft) { get; set; } | Margin kiri halaman yang diinginkan dalam piksel setelah konversi. |
| [MarginRight](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/marginright) { get; set; } | Margin kanan halaman yang diinginkan dalam piksel setelah konversi. |
| [MarginTop](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/margintop) { get; set; } | Margin atas halaman yang diinginkan dalam piksel setelah konversi. |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Nomor halaman untuk memulai konversi. |
| [PageOrientation](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/pageorientation) { get; set; } | Orientasi halaman yang diinginkan setelah konversi |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | Daftar indeks halaman yang akan dikonversi. Harus ditentukan untuk mengonversi halaman tertentu. |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Jumlah halaman yang akan dikonversi mulai dari`Nomor halaman` . |
| [PageSize](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/pagesize) { get; set; } | Ukuran halaman yang diinginkan setelah konversi |
| [Password](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/password) { get; set; } | Tetapkan properti ini jika Anda ingin melindungi dokumen yang dikonversi dengan kata sandi. |
| [PdfRecognitionMode](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/pdfrecognitionmode) { get; set; } | Mode pengenalan saat mengonversi dari pdf |
| [RtfOptions](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/rtfoptions) { get; set; } | Opsi konversi khusus RTF |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Opsi khusus tanda air |
| [Width](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/width) { get; set; } | Lebar halaman yang diinginkan setelah konversi. |
| [Zoom](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/zoom) { get; set; } | Menentukan tingkat pembesaran dalam persentase. Defaultnya adalah 100. Zoom default didukung hingga Microsoft Word 2010. Mulai dari Microsoft Word 2013 zoom default tidak lagi disetel ke dokumen, melainkan tampaknya menggunakan faktor zoom dari dokumen terakhir yang dibuka. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Klon instance opsi saat ini. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Menentukan apakah dua instance objek sama. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Menentukan apakah dua instance objek sama. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Berfungsi sebagai fungsi hash default. |

### Lihat juga

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [WordProcessingFileType](../../groupdocs.conversion.filetypes/wordprocessingfiletype)
* interface [IPageMarginConvertOptions](../ipagemarginconvertoptions)
* interface [IPageOrientationConvertOptions](../ipageorientationconvertoptions)
* interface [IPageSizeConvertOptions](../ipagesizeconvertoptions)
* interface [IPdfRecognitionModeOptions](../ipdfrecognitionmodeoptions)
* ruang nama [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* perakitan [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
