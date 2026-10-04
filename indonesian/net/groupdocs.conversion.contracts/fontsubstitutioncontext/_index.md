---
title: "FontSubstitutionContext"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Menjelaskan satu substitusi font yang terjadi saat memuat atau merender dokumen sumber. Instance diteruskan ke OnFontSubstituted../groupdocs.conversion/conversionevents/onfontsubstituted."
type: docs
weight: 250
url: /id/net/groupdocs.conversion.contracts/fontsubstitutioncontext/
---
## FontSubstitutionContext class

Menjelaskan satu substitusi font yang terjadi saat memuat atau merender dokumen sumber. Instance diteruskan ke [`OnFontSubstituted`](../../groupdocs.conversion/conversionevents/onfontsubstituted).

```csharp
public sealed class FontSubstitutionContext
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [FontSubstitutionContext](fontsubstitutioncontext)(string, string, string, string) | Membuat [`FontSubstitutionContext`](../fontsubstitutioncontext) baru. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [OriginalFontName](../../groupdocs.conversion.contracts/fontsubstitutioncontext/originalfontname) { get; } | Nama font yang direferensikan oleh dokumen sumber tetapi tidak tersedia untuk pipeline konversi. |
| [Reason](../../groupdocs.conversion.contracts/fontsubstitutioncontext/reason) { get; } | Pesan substitusi persis seperti yang dilaporkan oleh pipeline konversi, verbatim dan tidak diparse. Untuk dokumen yang mengekspos nama font secara struktural ini dapat menjadi `null` (gunakan [`OriginalFontName`](./originalfontname) / [`SubstituteFontName`](./substitutefontname)); untuk yang lain ia membawa deskripsi yang dapat dibaca manusia secara lengkap, yang menyebutkan baik font yang hilang maupun font pengganti. |
| [SourceFileName](../../groupdocs.conversion.contracts/fontsubstitutioncontext/sourcefilename) { get; } | Nama file dari dokumen sumber yang sedang dikonversi. Ketika sumber diberikan sebagai aliran yang bukan FileStream, ini berisi pengidentifikasi yang dihasilkan alih-alih nama file yang sebenarnya. |
| [SubstituteFontName](../../groupdocs.conversion.contracts/fontsubstitutioncontext/substitutefontname) { get; } | Nama font yang digunakan sebagai pengganti. Bisa jadi `null` untuk dokumen yang mesinnya melaporkan substitusi hanya sebagai teks deskriptif — dalam kasus itu baca [`Reason`](./reason). |

### Lihat Juga

* namespace [GroupDocs.Conversion.Contracts](../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
