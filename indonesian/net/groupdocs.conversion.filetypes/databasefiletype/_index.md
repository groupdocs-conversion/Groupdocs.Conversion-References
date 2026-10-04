---
title: "DatabaseFileType"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Mendefinisikan dokumen basis data. Menyertakan tipe file berikut Nsf./databasefiletype/nsfLog./databasefiletype/logSql./databasefiletype/sql"
type: docs
weight: 1090
url: /id/net/groupdocs.conversion.filetypes/databasefiletype/
---
## DatabaseFileType class

Mendefinisikan dokumen basis data. Menyertakan tipe file berikut: [`Nsf`](./nsf)[`Log`](./log)[`Sql`](./sql)

```csharp
public sealed class DatabaseFileType : FileType
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [DatabaseFileType](databasefiletype)() | Konstruktor Serialisasi |

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
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Membandingkan objek saat ini dengan objek lain. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Mengimplementasikan [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Menentukan apakah dua instance objek sama. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Berfungsi sebagai fungsi hash default. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Representasi string |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| static readonly [Log](../../groupdocs.conversion.filetypes/databasefiletype/log) | File dengan ekstensi .log berisi daftar teks biasa dengan cap waktu. Biasanya, detail aktivitas tertentu dicatat oleh perangkat lunak atau sistem operasi untuk membantu pengembang atau pengguna melacak apa yang terjadi pada periode waktu tertentu. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/database/log). |
| static readonly [Nsf](../../groupdocs.conversion.filetypes/databasefiletype/nsf) | File dengan ekstensi .nsf (Notes Storage Facility) adalah format file basis data yang digunakan oleh perangkat lunak IBM Notes, yang sebelumnya dikenal sebagai Lotus Notes. Ia mendefinisikan skema untuk menyimpan berbagai jenis objek seperti email, janji, dokumen, formulir, dan tampilan. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/database/nsf). |
| static readonly [Sql](../../groupdocs.conversion.filetypes/databasefiletype/sql) | File dengan ekstensi .sql adalah file Structured Query Language (SQL) yang berisi kode untuk bekerja dengan basis data relasional. Ia digunakan untuk menulis pernyataan SQL untuk operasi CRUD (Create, Read, Update, and Delete) pada basis data. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/database/sql). |

### Lihat Juga

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
