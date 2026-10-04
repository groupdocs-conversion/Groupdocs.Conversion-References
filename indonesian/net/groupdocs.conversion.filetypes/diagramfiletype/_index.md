---
title: "DiagramFileType"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Mendefinisikan dokumen Diagram. Menyertakan tipe berikut Drawio./diagramfiletype/drawio Mmd./diagramfiletype/mmd Vdw./diagramfiletype/vdw Vdx./diagramfiletype/vdx Vsd./diagramfiletype/vsd Vsdm./diagramfiletype/vsdm Vsdx./diagramfiletype/vsdx Vss./diagramfiletype/vss Vssm./diagramfiletype/vssm Vssx./diagramfiletype/vssx Vst./diagramfiletype/vst Vstm./diagramfiletype/vstm Vstx./diagramfiletype/vstx Vsx./diagramfiletype/vsx Vtx./diagramfiletype/vtx."
type: docs
weight: 1100
url: /id/net/groupdocs.conversion.filetypes/diagramfiletype/
---
## DiagramFileType class

Mendefinisikan dokumen Diagram. Menyertakan tipe berikut: [`Drawio`](./drawio), [`Mmd`](./mmd), [`Vdw`](./vdw), [`Vdx`](./vdx), [`Vsd`](./vsd), [`Vsdm`](./vsdm), [`Vsdx`](./vsdx), [`Vss`](./vss), [`Vssm`](./vssm), [`Vssx`](./vssx), [`Vst`](./vst), [`Vstm`](./vstm), [`Vstx`](./vstx), [`Vsx`](./vsx), [`Vtx`](./vtx).

```csharp
public sealed class DiagramFileType : FileType
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [DiagramFileType](diagramfiletype)() | Konstruktor Serialisasi |

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
| static readonly [Drawio](../../groupdocs.conversion.filetypes/diagramfiletype/drawio) | File dengan ekstensi DRAWIO adalah diagram yang dibuat dengan diagrams.net (sebelumnya draw.io). File ini disimpan dalam format file XML dengan elemen akar mxfile dan menyimpan konten serta pemformatan elemen diagram seperti teks, gambar, tata letak, bentuk, dan posisi. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/web/drawio). |
| static readonly [Mmd](../../groupdocs.conversion.filetypes/diagramfiletype/mmd) | File dengan ekstensi MMD adalah diagram yang ditulis dalam bahasa markup Mermaid. File ini disimpan sebagai dokumen teks biasa yang dimulai dengan deklarasi diagram, seperti flowchart atau sequenceDiagram, diikuti oleh definisi node dan koneksi di antara mereka. Pelajari lebih lanjut tentang format file ini [di sini](https://mermaid.js.org/intro/). |
| static readonly [Vdw](../../groupdocs.conversion.filetypes/diagramfiletype/vdw) | VDW adalah format file Visio Graphics Service yang menentukan aliran dan penyimpanan yang diperlukan untuk merender gambar Web. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/web/vdw). |
| static readonly [Vdx](../../groupdocs.conversion.filetypes/diagramfiletype/vdx) | Setiap gambar atau diagram yang dibuat di Microsoft Visio, tetapi disimpan dalam format XML memiliki ekstensi .VDX. File XML gambar Visio dibuat dalam perangkat lunak Visio, yang dikembangkan oleh Microsoft. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/image/vdx). |
| static readonly [Vsd](../../groupdocs.conversion.filetypes/diagramfiletype/vsd) | File VSD adalah gambar yang dibuat dengan aplikasi Microsoft Visio untuk merepresentasikan berbagai objek grafis dan interkoneksi di antara mereka. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/image/vsd). |
| static readonly [Vsdm](../../groupdocs.conversion.filetypes/diagramfiletype/vsdm) | File dengan ekstensi VSDM adalah file gambar yang dibuat dengan aplikasi Microsoft Visio yang mendukung makro. File VSDM adalah gambar OPC/XML yang mirip dengan VSDX, tetapi juga menyediakan kemampuan untuk menjalankan makro saat file dibuka. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/image/vsdm). |
| static readonly [Vsdx](../../groupdocs.conversion.filetypes/diagramfiletype/vsdx) | File dengan ekstensi .VSDX mewakili format file Microsoft Visio yang diperkenalkan sejak Microsoft Office 2013 ke atas. Format ini dikembangkan untuk menggantikan format file biner, .VSD, yang didukung oleh versi Microsoft Visio sebelumnya. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/image/vsdx). |
| static readonly [Vss](../../groupdocs.conversion.filetypes/diagramfiletype/vss) | VSS adalah file stensil yang dibuat dengan Microsoft Visio 2007 dan sebelumnya. File stensil menyediakan objek gambar yang dapat dimasukkan ke dalam gambar Visio .VSD. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/image/vss). |
| static readonly [Vssm](../../groupdocs.conversion.filetypes/diagramfiletype/vssm) | File dengan ekstensi .VSSM adalah file Stensil Microsoft Visio yang mendukung makro. File VSSM saat dibuka memungkinkan menjalankan makro untuk mencapai pemformatan dan penempatan bentuk yang diinginkan dalam diagram. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/image/vssm). |
| static readonly [Vssx](../../groupdocs.conversion.filetypes/diagramfiletype/vssx) | File dengan ekstensi .VSSX adalah stensil gambar yang dibuat dengan Microsoft Visio 2013 ke atas. Format file VSSX dapat dibuka dengan Visio 2013 ke atas. File Visio dikenal untuk representasi berbagai elemen gambar seperti kumpulan bentuk, penghubung, diagram alur, tata letak jaringan, diagram UML. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/image/vssx). |
| static readonly [Vst](../../groupdocs.conversion.filetypes/diagramfiletype/vst) | File dengan ekstensi VST adalah file gambar vektor yang dibuat dengan Microsoft Visio dan berfungsi sebagai templat untuk membuat file lebih lanjut. File templat ini berformat file biner dan berisi tata letak serta pengaturan default yang digunakan untuk membuat gambar Visio baru. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/image/vst). |
| static readonly [Vstm](../../groupdocs.conversion.filetypes/diagramfiletype/vstm) | File dengan ekstensi VSTM adalah file templat yang dibuat dengan Microsoft Visio yang mendukung makro. Tidak seperti file VSDX, file yang dibuat dari templat VSTM dapat menjalankan makro yang dikembangkan dalam kode Visual Basic for Applications (VBA). Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/image/vstm). |
| static readonly [Vstx](../../groupdocs.conversion.filetypes/diagramfiletype/vstx) | File dengan ekstensi VSTX adalah file templat gambar yang dibuat dengan Microsoft Visio 2013 ke atas. File VSTX ini menyediakan titik awal untuk membuat gambar Visio, disimpan sebagai file .VSDX, dengan tata letak dan pengaturan default. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/image/vstx). |
| static readonly [Vsx](../../groupdocs.conversion.filetypes/diagramfiletype/vsx) | File dengan ekstensi .VSX merujuk pada stensil yang terdiri dari gambar dan bentuk yang digunakan untuk membuat diagram di Microsoft Visio. File VSX disimpan dalam format file XML dan didukung hingga Visio 2013. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/image/vsx). |
| static readonly [Vtx](../../groupdocs.conversion.filetypes/diagramfiletype/vtx) | File dengan ekstensi VTX adalah templat gambar Microsoft Visio yang disimpan ke disk dalam format file XML. Templat ini bertujuan menyediakan file dengan pengaturan dasar yang dapat digunakan untuk membuat banyak file Visio dengan pengaturan yang sama. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/image/vtx). |

### Lihat Juga

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
