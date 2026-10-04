---
title: "PdfRecognitionMode"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Memungkinkan mengontrol bagaimana dokumen PDF dikonversi menjadi dokumen pengolah kata."
type: docs
weight: 2160
url: /id/net/groupdocs.conversion.options.convert/pdfrecognitionmode/
---
## PdfRecognitionMode class

Memungkinkan mengontrol bagaimana dokumen PDF dikonversi menjadi dokumen pengolah kata.

```csharp
public sealed class PdfRecognitionMode : Enumeration
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Membandingkan objek saat ini dengan objek lain. |
| virtual [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(Enumeration) | Menentukan apakah dua instance objek sama. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Menentukan apakah dua instance objek sama. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Berfungsi sebagai fungsi hash default. |
| override [ToString](../../groupdocs.conversion.contracts/enumeration/tostring)() | Mengembalikan string yang merepresentasikan objek saat ini. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| static readonly [Flow](../../groupdocs.conversion.options.convert/pdfrecognitionmode/flow) | Mode pengenalan penuh, mesin melakukan pengelompokan dan analisis multi‑tingkat untuk mengembalikan maksud penulis dokumen asli dan menghasilkan dokumen yang dapat diedit secara maksimal. Kekurangannya adalah dokumen output mungkin terlihat berbeda dari file PDF asli. |
| static readonly [Textbox](../../groupdocs.conversion.options.convert/pdfrecognitionmode/textbox) | Mode ini cepat dan baik untuk mempertahankan tampilan asli file PDF secara maksimal, tetapi kemampuan mengedit dokumen yang dihasilkan dapat terbatas. Setiap blok teks yang dikelompokkan secara visual dalam file PDF asli dikonversi menjadi kotak teks dalam dokumen hasil. Ini menghasilkan kemiripan maksimal antara dokumen output dan file PDF asli. Dokumen output akan terlihat bagus, tetapi akan sepenuhnya terdiri dari kotak teks dan dapat membuat penyuntingan lebih lanjut dokumen di Microsoft Word menjadi cukup sulit. Ini adalah mode default. |

### Lihat Juga

* class [Enumeration](../../groupdocs.conversion.contracts/enumeration)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
