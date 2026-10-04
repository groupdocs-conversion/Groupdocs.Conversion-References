---
title: "ProjectManagementFileType"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Menentukan format file Proyek yang dibuat oleh perangkat lunak Manajemen Proyek seperti Microsoft Project, Primavera P6, dll. File proyek adalah kumpulan tugas, sumber daya, dan penjadwalannya untuk menghasilkan output terukur berupa produk atau layanan. Dokumen manajemen proyek. Menyertakan tipe file berikut Mpp./projectmanagementfiletype/mpp Mpt./projectmanagementfiletype/mpt Mpx./projectmanagementfiletype/mpx. Pelajari lebih lanjut tentang format Manajemen Proyek herehttps//wiki.fileformat.com/projectmanagement."
type: docs
weight: 1220
url: /id/net/groupdocs.conversion.filetypes/projectmanagementfiletype/
---
## ProjectManagementFileType class

Menentukan format file Proyek yang dibuat oleh perangkat lunak Manajemen Proyek seperti Microsoft Project, Primavera P6, dll. File proyek adalah kumpulan tugas, sumber daya, dan penjadwalannya untuk menghasilkan output terukur berupa produk atau layanan. Dokumen manajemen proyek. Menyertakan tipe file berikut: [`Mpp`](./mpp), [`Mpt`](./mpt), [`Mpx`](./mpx). Pelajari lebih lanjut tentang format Manajemen Proyek [here](https://wiki.fileformat.com/project-management).

```csharp
public sealed class ProjectManagementFileType : FileType
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [ProjectManagementFileType](projectmanagementfiletype)() | Konstruktor Serialisasi |

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
| static readonly [Mpp](../../groupdocs.conversion.filetypes/projectmanagementfiletype/mpp) | MPP adalah file data Microsoft Project yang menyimpan informasi terkait manajemen proyek secara terintegrasi. Pelajari lebih lanjut tentang format file ini [here](https://wiki.fileformat.com/project-management/mpp). |
| static readonly [Mpt](../../groupdocs.conversion.filetypes/projectmanagementfiletype/mpt) | File templat Microsoft Project berisi informasi dasar dan struktur bersama dengan pengaturan dokumen untuk membuat file .MPP. Pelajari lebih lanjut tentang format file ini [here](https://wiki.fileformat.com/project-management/mpt). |
| static readonly [Mpx](../../groupdocs.conversion.filetypes/projectmanagementfiletype/mpx) | Microsoft Exchange File Format adalah format file ASCII untuk mentransfer informasi proyek antara Microsoft Project (MSP) dan aplikasi lain yang mendukung format file MPX seperti Primavera Project Planner, Sciforma, dan Timerline Precision Estimating. Pelajari lebih lanjut tentang format file ini [here](https://wiki.fileformat.com/project-management/mpx). |
| static readonly [Xer](../../groupdocs.conversion.filetypes/projectmanagementfiletype/xer) | Format file XER adalah format file proyek proprietari yang digunakan oleh aplikasi perencanaan dan manajemen proyek Primavera P6. Pelajari lebih lanjut tentang format file ini [here](https://docs.fileformat.com/project-management/xer). |

### Lihat Juga

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
