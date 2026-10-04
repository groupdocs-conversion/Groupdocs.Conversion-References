---
title: "PdfOptimizationOptions"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Mendefinisikan opsi optimasi Pdf."
type: docs
weight: 2120
url: /id/net/groupdocs.conversion.options.convert/pdfoptimizationoptions/
---
## PdfOptimizationOptions class

Mendefinisikan opsi optimasi Pdf.

```csharp
public sealed class PdfOptimizationOptions : ValueObject
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [PdfOptimizationOptions](pdfoptimizationoptions)() | Menginisialisasi instance baru dari kelas [`PdfOptimizationOptions`](../pdfoptimizationoptions). |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [CompressImages](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/compressimages) { get; set; } | Jika CompressImages diatur ke `true`, semua gambar dalam dokumen akan dikompresi ulang. Kompresi ditentukan oleh properti ImageQuality. |
| [FontSubsetStrategy](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/fontsubsetstrategy) { get; set; } | Atur strategi subset font |
| [ImageQuality](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/imagequality) { get; set; } | Nilai dalam persen dimana 100% berarti kualitas dan ukuran gambar tidak berubah. Untuk mengurangi ukuran gambar, atur properti ini menjadi kurang dari 100 |
| [LinkDuplicateStreams](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/linkduplicatestreams) { get; set; } | Tautkan aliran duplikat |
| [RemoveUnusedObjects](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/removeunusedobjects) { get; set; } | Hapus objek yang tidak terpakai |
| [RemoveUnusedStreams](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/removeunusedstreams) { get; set; } | Hapus aliran yang tidak terpakai |
| [UnembedFonts](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/unembedfonts) { get; set; } | Jadikan font tidak disematkan jika diatur ke true |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Menentukan apakah dua instance objek sama. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Menentukan apakah dua instance objek sama. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Berfungsi sebagai fungsi hash default. |

### Lihat Juga

* class [ValueObject](../../groupdocs.conversion.contracts/valueobject)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
