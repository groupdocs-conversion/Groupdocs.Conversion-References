---
title: "FileType"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Kelas dasar tipe file"
type: docs
weight: 1130
url: /id/net/groupdocs.conversion.filetypes/filetype/
---
## FileType class

Kelas dasar tipe file

```csharp
public class FileType : Enumeration
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [FileType](filetype)() | Konstruktor Serialisasi |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Deskripsi tipe file |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | Ekstensi file |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | Keluarga file |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Format file |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [FromExtension](../../groupdocs.conversion.filetypes/filetype/fromextension)(string) | Mendapatkan FileType untuk fileExtension yang diberikan |
| static [FromFilename](../../groupdocs.conversion.filetypes/filetype/fromfilename)(string) | Mengembalikan FileType untuk fileName yang ditentukan |
| static [FromStream](../../groupdocs.conversion.filetypes/filetype/fromstream)(Stream) | Mengembalikan FileType untuk aliran dokumen yang diberikan |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Membandingkan objek saat ini dengan objek lain. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals#equals)(Enumeration) | Mengimplementasikan [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Menentukan apakah dua instance objek sama. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Berfungsi sebagai fungsi hash default. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Representasi string |
| static [GetAll&lt;T&gt;](../../groupdocs.conversion.filetypes/filetype/getall)() | Mengembalikan semua nilai enumerasi. |
| [implicit operator](../../groupdocs.conversion.filetypes/filetype/op_implicit) | Konversi implisit ke string |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| static readonly [Unknown](../../groupdocs.conversion.filetypes/filetype/unknown) | Tipe file tidak diketahui |

### Lihat Juga

* class [Enumeration](../../groupdocs.conversion.contracts/enumeration)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
