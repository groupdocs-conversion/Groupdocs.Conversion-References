---
title: "PageSizeOptions"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Mewakili opsi yang mendukung ukuran halaman."
type: docs
weight: 2990
url: /id/net/groupdocs.conversion.options/pagesizeoptions/
---
## PageSizeOptions class

Mewakili opsi yang mendukung ukuran halaman.

```csharp
public sealed class PageSizeOptions : ValueObject
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [PageSizeOptions](pagesizeoptions)() | Konstruktor default. Menginisialisasi [`PageSize`](./pagesize) menjadi [`Unset`](../pagesize/unset). |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [PageHeight](../../groupdocs.conversion.options/pagesizeoptions/pageheight) { get; set; } | Tinggi halaman dalam poin yang akan diterapkan sebelum konversi. Ketika diatur, [`PageSize`](./pagesize) secara otomatis diubah menjadi [`Custom`](../pagesize/custom). |
| [PageSize](../../groupdocs.conversion.options/pagesizeoptions/pagesize) { get; set; } | Menerapkan [`PageSize`](../pagesize) |
| [PageWidth](../../groupdocs.conversion.options/pagesizeoptions/pagewidth) { get; set; } | Lebar halaman dalam poin yang akan diterapkan sebelum konversi. Ketika diatur, [`PageSize`](./pagesize) secara otomatis diubah menjadi [`Custom`](../pagesize/custom). |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Menentukan apakah dua instance objek sama. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Menentukan apakah dua instance objek sama. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Berfungsi sebagai fungsi hash default. |

### Lihat Juga

* class [ValueObject](../../groupdocs.conversion.contracts/valueobject)
* namespace [GroupDocs.Conversion.Options](../../groupdocs.conversion.options)
* assembly [GroupDocs.Conversion](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
