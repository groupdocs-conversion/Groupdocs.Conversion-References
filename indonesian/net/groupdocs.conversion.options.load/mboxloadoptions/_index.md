---
title: "MboxLoadOptions"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Opsi untuk memuat dokumen Mbox."
type: docs
weight: 2670
url: /id/net/groupdocs.conversion.options.load/mboxloadoptions/
---
## MboxLoadOptions class

Opsi untuk memuat dokumen Mbox.

```csharp
public sealed class MboxLoadOptions : LoadOptions, IDocumentsContainerLoadOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [MboxLoadOptions](mboxloadoptions)() | Menginisialisasi instance baru dari kelas [`MboxLoadOptions`](../mboxloadoptions). |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [ConvertOwned](../../groupdocs.conversion.options.load/mboxloadoptions/convertowned) { get; } | Mengimplementasikan [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) Readonly. Diatur ke true. Dokumen yang dimiliki akan dikonversi. |
| [ConvertOwner](../../groupdocs.conversion.options.load/mboxloadoptions/convertowner) { get; } | Mengimplementasikan [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) Readonly. Diatur ke false. Pemilik tidak akan dikonversi. |
| [Depth](../../groupdocs.conversion.options.load/mboxloadoptions/depth) { get; set; } | Mengimplementasikan [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth) Default: 3 |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Tipe berkas dokumen input. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.load/mboxloadoptions/clone)() | Mengkloning instance saat ini. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Menentukan apakah dua instance objek sama. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Menentukan apakah dua instance objek sama. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Berfungsi sebagai fungsi hash default. |

### Lihat Juga

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
