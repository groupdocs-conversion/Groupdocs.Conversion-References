---
title: "WordProcessingBookmarksOptions"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Opsi untuk menangani bookmark dalam WordProcessing."
type: docs
weight: 2930
url: /id/net/groupdocs.conversion.options.load/wordprocessingbookmarksoptions/
---
## WordProcessingBookmarksOptions class

Opsi untuk menangani bookmark dalam WordProcessing.

```csharp
public class WordProcessingBookmarksOptions : ValueObject
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [WordProcessingBookmarksOptions](wordprocessingbookmarksoptions)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [BookmarksOutlineLevel](../../groupdocs.conversion.options.load/wordprocessingbookmarksoptions/bookmarksoutlinelevel) { get; set; } | Menentukan level default dalam outline dokumen tempat menampilkan bookmark Word. Default adalah 0. Rentang yang valid adalah 0 hingga 9. |
| [ExpandedOutlineLevels](../../groupdocs.conversion.options.load/wordprocessingbookmarksoptions/expandedoutlinelevels) { get; set; } | Menentukan berapa banyak level dalam outline dokumen yang akan ditampilkan dalam keadaan terbuka saat file dilihat. Default adalah 0. Rentang yang valid adalah 0 hingga 9. Catatan bahwa opsi ini tidak akan berfungsi saat menyimpan ke XPS. |
| [HeadingsOutlineLevels](../../groupdocs.conversion.options.load/wordprocessingbookmarksoptions/headingsoutlinelevels) { get; set; } | Menentukan berapa banyak level heading (paragraf yang diformat dengan gaya Heading) yang akan dimasukkan ke dalam outline dokumen. Default adalah 0. Rentang yang valid adalah 0 hingga 9. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Menentukan apakah dua instance objek sama. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Menentukan apakah dua instance objek sama. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Berfungsi sebagai fungsi hash default. |

### Lihat Juga

* class [ValueObject](../../groupdocs.conversion.contracts/valueobject)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
