---
title: "PdfOptions"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Opsi untuk konversi ke tipe file Pdf."
type: docs
weight: 2130
url: /id/net/groupdocs.conversion.options.convert/pdfoptions/
---
## PdfOptions class

Opsi untuk konversi ke tipe file Pdf.

```csharp
public sealed class PdfOptions : ValueObject, IZoomConvertOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [PdfOptions](pdfoptions)() | Menginisialisasi instance baru dari kelas [`PdfOptions`](../pdfoptions). |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [DocumentInfo](../../groupdocs.conversion.options.convert/pdfoptions/documentinfo) { get; set; } | Informasi meta dari dokumen PDF. |
| [FormattingOptions](../../groupdocs.conversion.options.convert/pdfoptions/formattingoptions) { get; set; } | Opsi pemformatan PDF |
| [Grayscale](../../groupdocs.conversion.options.convert/pdfoptions/grayscale) { get; set; } | Konversi PDF dari ruang warna RGB ke skala abu-abu |
| [Linearize](../../groupdocs.conversion.options.convert/pdfoptions/linearize) { get; set; } | Lineariskan Dokumen PDF untuk Web |
| [OptimizationOptions](../../groupdocs.conversion.options.convert/pdfoptions/optimizationoptions) { get; set; } | Opsi optimasi PDF |
| [PdfFormat](../../groupdocs.conversion.options.convert/pdfoptions/pdfformat) { get; set; } | Mengatur format PDF dari dokumen yang dikonversi. |
| [RemovePdfACompliance](../../groupdocs.conversion.options.convert/pdfoptions/removepdfacompliance) { get; set; } | Menghapus kepatuhan PDF/A |
| [Zoom](../../groupdocs.conversion.options.convert/pdfoptions/zoom) { get; set; } | Menentukan tingkat zoom dalam persentase. Defaultnya 100. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Menentukan apakah dua instance objek sama. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Menentukan apakah dua instance objek sama. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Berfungsi sebagai fungsi hash default. |

### Lihat Juga

* class [ValueObject](../../groupdocs.conversion.contracts/valueobject)
* interface [IZoomConvertOptions](../izoomconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
