---
title: "WebConvertOptions"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Opsi untuk konversi ke tipe file Web."
type: docs
weight: 2320
url: /id/net/groupdocs.conversion.options.convert/webconvertoptions/
---
## WebConvertOptions class

Opsi untuk konversi ke tipe file Web.

```csharp
public class WebConvertOptions : CommonConvertOptions<WebFileType>, IUsePdfConvertOptions, 
    IZoomConvertOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [WebConvertOptions](webconvertoptions)() | Menginisialisasi instance baru dari kelas [`WebConvertOptions`](../webconvertoptions) class. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [EmbedFontResources](../../groupdocs.conversion.options.convert/webconvertoptions/embedfontresources) { get; set; } | Menentukan apakah akan menyematkan sumber daya font dalam HTML utama. Defaultnya false. Catatan: Jika FixedLayout diatur ke true, sumber daya font akan selalu disematkan. |
| [FixedLayout](../../groupdocs.conversion.options.convert/webconvertoptions/fixedlayout) { get; set; } | Jika `true` tata letak tetap akan digunakan, misalnya elemen HTML yang diposisikan secara absolut. Default: true |
| [FixedLayoutShowBorders](../../groupdocs.conversion.options.convert/webconvertoptions/fixedlayoutshowborders) { get; set; } | Tampilkan batas halaman saat mengonversi ke tata letak tetap. Defaultnya True. |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Tipe file yang diinginkan untuk mengonversi dokumen input. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Mengimplementasikan [`Format`](../iconvertoptions/format) |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Mengimplementasikan [`PageNumber`](../ipagedconvertoptions/pagenumber) |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | Menerapkan [`Pages`](../ipagerangedconvertoptions/pages) |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Menerapkan [`PagesCount`](../ipagedconvertoptions/pagescount) |
| [SlideShow](../../groupdocs.conversion.options.convert/webconvertoptions/slideshow) { get; set; } | Hanya berlaku untuk mengonversi presentasi ke [`Html`](../../groupdocs.conversion.filetypes/webfiletype/html) atau [`Htm`](../../groupdocs.conversion.filetypes/webfiletype/htm), dan diabaikan untuk konversi lainnya. Menentukan apakah presentasi menjadi slideshow HTML interaktif dengan transisi slide dan animasi bentuk, alih-alih halaman HTML statis default. Defaultnya false. |
| [UsePdf](../../groupdocs.conversion.options.convert/webconvertoptions/usepdf) { get; set; } | Jika `true`, input pertama-tama dikonversi ke PDF dan kemudian ke format yang diinginkan. |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Menerapkan [`Watermark`](../iwatermarkedconvertoptions/watermark) |
| [Zoom](../../groupdocs.conversion.options.convert/webconvertoptions/zoom) { get; set; } | Menentukan tingkat zoom dalam persentase. Defaultnya 100. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Menggandakan instance opsi saat ini. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Menentukan apakah dua instance objek sama. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Menentukan apakah dua instance objek sama. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Berfungsi sebagai fungsi hash default. |

### Lihat Juga

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [WebFileType](../../groupdocs.conversion.filetypes/webfiletype)
* interface [IUsePdfConvertOptions](../iusepdfconvertoptions)
* interface [IZoomConvertOptions](../izoomconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
