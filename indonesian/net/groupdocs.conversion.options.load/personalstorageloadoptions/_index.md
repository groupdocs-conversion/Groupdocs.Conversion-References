---
title: "PersonalStorageLoadOptions"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Opsi untuk memuat dokumen penyimpanan pribadi."
type: docs
weight: 2750
url: /id/net/groupdocs.conversion.options.load/personalstorageloadoptions/
---
## PersonalStorageLoadOptions class

Opsi untuk memuat dokumen penyimpanan pribadi.

```csharp
public sealed class PersonalStorageLoadOptions : LoadOptions, IDocumentsContainerLoadOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [PersonalStorageLoadOptions](personalstorageloadoptions)() | Menginisialisasi instance baru dari kelas [`PersonalStorageLoadOptions`](../personalstorageloadoptions). |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [ConvertOwned](../../groupdocs.conversion.options.load/personalstorageloadoptions/convertowned) { get; } | Mengimplementasikan [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) Readonly. Diatur ke true. Dokumen yang dimiliki akan dikonversi. |
| [ConvertOwner](../../groupdocs.conversion.options.load/personalstorageloadoptions/convertowner) { get; } | Mengimplementasikan [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) Readonly. Diatur ke false. Pemilik tidak akan dikonversi. |
| [Depth](../../groupdocs.conversion.options.load/personalstorageloadoptions/depth) { get; set; } | Mengimplementasikan [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth) Default: 3 |
| [Folder](../../groupdocs.conversion.options.load/personalstorageloadoptions/folder) { get; set; } | Folder yang akan diproses. Default adalah Inbox. |
| [Format](../../groupdocs.conversion.options.load/personalstorageloadoptions/format) { get; set; } | Tipe berkas dokumen input. Nilainya `null` sampai format ditetapkan, jadi periksa apakah `null` daripada membandingkannya dengan [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), yang tidak pernah sama. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Tipe berkas dokumen input. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.load/personalstorageloadoptions/clone)() | Mengkloning instance saat ini. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Menentukan apakah dua instance objek sama. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Menentukan apakah dua instance objek sama. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Berfungsi sebagai fungsi hash default. |

### Lihat Juga

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
