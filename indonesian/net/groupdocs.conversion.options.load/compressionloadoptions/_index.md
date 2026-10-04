---
title: "CompressionLoadOptions"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Opsi untuk memuat dokumen kompresi."
type: docs
weight: 2440
url: /id/net/groupdocs.conversion.options.load/compressionloadoptions/
---
## CompressionLoadOptions class

Opsi untuk memuat dokumen kompresi.

```csharp
public sealed class CompressionLoadOptions : LoadOptions, IDocumentsContainerLoadOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [CompressionLoadOptions](compressionloadoptions)() | Menginisialisasi instance baru dari kelas [`CompressionLoadOptions`](../compressionloadoptions). |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [ConvertOwned](../../groupdocs.conversion.options.load/compressionloadoptions/convertowned) { get; } | Mengimplementasikan [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) Readonly. Diatur ke true. Dokumen yang dimiliki akan dikonversi. |
| [ConvertOwner](../../groupdocs.conversion.options.load/compressionloadoptions/convertowner) { get; } | Mengimplementasikan [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) Readonly. Diatur ke false. Pemilik tidak akan dikonversi. |
| [Depth](../../groupdocs.conversion.options.load/compressionloadoptions/depth) { get; set; } | Mengimplementasikan [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth) Default: 3 |
| [Format](../../groupdocs.conversion.options.load/compressionloadoptions/format) { get; set; } | Tipe berkas dokumen input. Nilainya `null` sampai format ditetapkan, jadi periksa apakah `null` daripada membandingkannya dengan [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), yang tidak pernah sama. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Tipe berkas dokumen input. |
| [Password](../../groupdocs.conversion.options.load/compressionloadoptions/password) { get; set; } | Atur kata sandi untuk memuat dokumen yang dilindungi. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Menentukan apakah dua instance objek sama. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Menentukan apakah dua instance objek sama. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Berfungsi sebagai fungsi hash default. |

### Lihat Juga

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
