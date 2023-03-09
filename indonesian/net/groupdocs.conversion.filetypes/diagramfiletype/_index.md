---
title: DiagramFileType
second_title: GroupDocs.Konversi untuk Referensi .NET API
description: Mendefinisikan dokumen Diagram. Termasuk jenis berikut Vdw./diagramfiletype/vdw  Vdx./diagramfiletype/vdx  Vsd./diagramfiletype/vsd  Vsdm./diagramfiletype/vsdm  Vsdx./diagramfiletype/vsdx  Vss./diagramfiletype/vss  Vssm./diagramfiletype/vssm  Vssx./diagramfiletype/vssx  Vst./diagramfiletype/vst  Vstm./diagramfiletype/vstm  Vstx./diagramfiletype/vstx  Vsx./diagramfiletype/vsx  Vtx./diagramfiletype/vtx .
type: docs
weight: 900
url: /id/net/groupdocs.conversion.filetypes/diagramfiletype/
---
## DiagramFileType class

Mendefinisikan dokumen Diagram. Termasuk jenis berikut: [`Vdw`](./vdw) , [`Vdx`](./vdx) , [`Vsd`](./vsd) , [`Vsdm`](./vsdm) , [`Vsdx`](./vsdx) , [`Vss`](./vss) , [`Vssm`](./vssm) , [`Vssx`](./vssx) , [`Vst`](./vst) , [`Vstm`](./vstm) , [`Vstx`](./vstx) , [`Vsx`](./vsx) , [`Vtx`](./vtx) .

```csharp
public sealed class DiagramFileType : FileType
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [DiagramFileType](diagramfiletype)() | Konstruktor serialisasi |

## Properti

| Nama | Keterangan |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Deskripsi jenis file |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | Ekstensi file |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | Keluarga file |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Format file |

## Metode

| Nama | Keterangan |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Membandingkan objek saat ini dengan yang lain. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Menentukan apakah dua instance objek sama. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Menentukan apakah dua instance objek sama. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Berfungsi sebagai fungsi hash default. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Representasi string |

## Bidang

| Nama | Keterangan |
| --- | --- |
| static readonly [Vdw](../../groupdocs.conversion.filetypes/diagramfiletype/vdw) | VDW adalah format file Visio Graphics Service yang menentukan aliran dan penyimpanan yang diperlukan untuk merender gambar Web. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/web/vdw) . |
| static readonly [Vdx](../../groupdocs.conversion.filetypes/diagramfiletype/vdx) | Setiap gambar atau bagan yang dibuat di Microsoft Visio, tetapi disimpan dalam format XML memiliki ekstensi .VDX. File XML gambar Visio dibuat dalam perangkat lunak Visio, yang dikembangkan oleh Microsoft. Pelajari selengkapnya tentang format file ini[Di Sini](https://wiki.fileformat.com/image/vdx) . |
| static readonly [Vsd](../../groupdocs.conversion.filetypes/diagramfiletype/vsd) | File VSD adalah gambar yang dibuat dengan aplikasi Microsoft Visio untuk mewakili berbagai objek grafis dan interkoneksi di antaranya. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/image/vsd) . |
| static readonly [Vsdm](../../groupdocs.conversion.filetypes/diagramfiletype/vsdm) | File dengan ekstensi VSDM adalah file gambar yang dibuat dengan aplikasi Microsoft Visio yang mendukung makro. File VSDM adalah gambar OPC/XML yang mirip dengan VSDX, tetapi juga menyediakan kemampuan untuk menjalankan makro saat file dibuka. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/image/vsdm) . |
| static readonly [Vsdx](../../groupdocs.conversion.filetypes/diagramfiletype/vsdx) | File dengan ekstensi .VSDX mewakili format file Microsoft Visio yang diperkenalkan dari Microsoft Office 2013 dan seterusnya. Ini dikembangkan untuk menggantikan format file biner, .VSD, yang didukung oleh versi Microsoft Visio sebelumnya. Pelajari selengkapnya tentang format file ini[Di Sini](https://wiki.fileformat.com/image/vsdx) . |
| static readonly [Vss](../../groupdocs.conversion.filetypes/diagramfiletype/vss) | VSS adalah file stensil yang dibuat dengan Microsoft Visio 2007 dan sebelumnya. File stensil menyediakan objek gambar yang dapat disertakan dalam gambar .VSD Visio. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/image/vss) . |
| static readonly [Vssm](../../groupdocs.conversion.filetypes/diagramfiletype/vssm) | File dengan ekstensi .VSSM adalah file Microsoft Visio Stencil yang mendukung menyediakan dukungan untuk makro. File VSSM saat dibuka memungkinkan menjalankan makro untuk mencapai pemformatan dan penempatan bentuk yang diinginkan dalam diagram. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/image/vssm) . |
| static readonly [Vssx](../../groupdocs.conversion.filetypes/diagramfiletype/vssx) | File dengan ekstensi .VSSX adalah stensil gambar yang dibuat dengan Microsoft Visio 2013 ke atas. Format file VSSX dapat dibuka dengan Visio 2013 ke atas. File Visio dikenal untuk representasi berbagai elemen gambar seperti kumpulan bentuk, konektor, bagan alur, tata letak jaringan, diagram UML, Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/image/vssx) . |
| static readonly [Vst](../../groupdocs.conversion.filetypes/diagramfiletype/vst) | File dengan ekstensi VST adalah file gambar vektor yang dibuat dengan Microsoft Visio dan berfungsi sebagai template untuk membuat file lebih lanjut. File template ini dalam format file biner dan berisi tata letak dan pengaturan default yang digunakan untuk pembuatan gambar Visio baru. Pelajari selengkapnya tentang format file ini[Di Sini](https://wiki.fileformat.com/image/vst) . |
| static readonly [Vstm](../../groupdocs.conversion.filetypes/diagramfiletype/vstm) | File dengan ekstensi VSTM adalah file template yang dibuat dengan Microsoft Visio yang mendukung makro. Tidak seperti file VSDX, file yang dibuat dari template VSTM dapat menjalankan makro yang dikembangkan dalam kode Visual Basic for Applications (VBA). Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/image/vstm) . |
| static readonly [Vstx](../../groupdocs.conversion.filetypes/diagramfiletype/vstx) | File dengan ekstensi VSTX menggambar file template yang dibuat dengan Microsoft Visio 2013 ke atas. File VSTX ini menyediakan titik awal untuk membuat gambar Visio, disimpan sebagai file .VSDX, dengan tata letak dan pengaturan default. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/image/vstx) . |
| static readonly [Vsx](../../groupdocs.conversion.filetypes/diagramfiletype/vsx) | File dengan ekstensi .VSX mengacu pada stensil yang terdiri dari gambar dan bentuk yang digunakan untuk membuat diagram di Microsoft Visio. File VSX disimpan dalam format file XML dan didukung hingga Visio 2013. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/image/vsx) . |
| static readonly [Vtx](../../groupdocs.conversion.filetypes/diagramfiletype/vtx) | File dengan ekstensi VTX adalah template gambar Microsoft Visio yang disimpan ke disk dalam format file XML. Template ditujukan untuk menyediakan file dengan pengaturan dasar yang dapat digunakan untuk membuat beberapa file Visio dengan pengaturan yang sama. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/image/vtx) . |

### Lihat juga

* class [FileType](../filetype)
* ruang nama [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* perakitan [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
