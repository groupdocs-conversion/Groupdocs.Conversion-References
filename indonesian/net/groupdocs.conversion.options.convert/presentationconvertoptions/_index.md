---
title: "PresentationConvertOptions"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Menjelaskan opsi untuk konversi ke tipe file Presentasi."
type: docs
weight: 2170
url: /id/net/groupdocs.conversion.options.convert/presentationconvertoptions/
---
## PresentationConvertOptions class

Menjelaskan opsi untuk konversi ke tipe file Presentasi.

```csharp
public class PresentationConvertOptions : CommonConvertOptions<PresentationFileType>, 
    IPasswordConvertOptions, IZoomConvertOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [PresentationConvertOptions](presentationconvertoptions)() | Menginisialisasi instance baru dari kelas [`PresentationConvertOptions`](../presentationconvertoptions). |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Tipe file yang diinginkan untuk mengonversi dokumen input. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Mengimplementasikan [`Format`](../iconvertoptions/format) |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Mengimplementasikan [`PageNumber`](../ipagedconvertoptions/pagenumber) |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | Menerapkan [`Pages`](../ipagerangedconvertoptions/pages) |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Menerapkan [`PagesCount`](../ipagedconvertoptions/pagescount) |
| [Password](../../groupdocs.conversion.options.convert/presentationconvertoptions/password) { get; set; } | Atur properti ini jika Anda ingin melindungi dokumen yang dikonversi dengan kata sandi. |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Menerapkan [`Watermark`](../iwatermarkedconvertoptions/watermark) |
| [Zoom](../../groupdocs.conversion.options.convert/presentationconvertoptions/zoom) { get; set; } | Menentukan tingkat zoom dalam persentase. Default adalah 100. Zoom default didukung hingga Microsoft Powerpoint 2010. Mulai dari Microsoft Powerpoint 2013, zoom default tidak lagi diatur ke dokumen, melainkan tampaknya menggunakan faktor zoom dari dokumen terakhir yang dibuka. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Menggandakan instance opsi saat ini. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Menentukan apakah dua instance objek sama. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Menentukan apakah dua instance objek sama. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Berfungsi sebagai fungsi hash default. |

### Lihat Juga

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [PresentationFileType](../../groupdocs.conversion.filetypes/presentationfiletype)
* interface [IPasswordConvertOptions](../ipasswordconvertoptions)
* interface [IZoomConvertOptions](../izoomconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
