---
title: "CadFileType"
second_title: "GroupDocs.Conversion untuk .NET API Reference"
description: "Mendefinisikan dokumen CAD (Computer Aided Design) yang digunakan untuk format file grafis 3D dan dapat berisi desain 2D atau 3D. Menyertakan tipe berikut Cf2./cadfiletype/cf2 Dgn./cadfiletype/dgn Dwf./cadfiletype/dwf Dwfx./cadfiletype/dwfx Dwg./cadfiletype/dwg Dwt./cadfiletype/dwt Dxf./cadfiletype/dxf Ifc./cadfiletype/ifc Igs./cadfiletype/igs Plt./cadfiletype/plt Stl./cadfiletype/stl. Pelajari lebih lanjut tentang format CAD di sinihttps//wiki.fileformat.com/cad."
type: docs
weight: 1070
url: /id/net/groupdocs.conversion.filetypes/cadfiletype/
---
## CadFileType class

Mendefinisikan dokumen CAD (Computer Aided Design) yang digunakan untuk format file grafis 3D dan dapat berisi desain 2D atau 3D. Menyertakan tipe berikut: [`Cf2`](./cf2)[`Dgn`](./dgn), [`Dwf`](./dwf), [`Dwfx`](./dwfx)[`Dwg`](./dwg), [`Dwt`](./dwt), [`Dxf`](./dxf), [`Ifc`](./ifc), [`Igs`](./igs), [`Plt`](./plt), [`Stl`](./stl). Pelajari lebih lanjut tentang format CAD [di sini](https://wiki.fileformat.com/cad).

```csharp
public sealed class CadFileType : FileType
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [CadFileType](cadfiletype)() | Konstruktor Serialisasi |

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
| static readonly [Cf2](../../groupdocs.conversion.filetypes/cadfiletype/cf2) | File Common File Format. File CAD yang berisi desain paket 3D atau data model lainnya; dapat diproses dan dipotong oleh mesin CAD/CAM, seperti perangkat pemotong die. |
| static readonly [Dgn](../../groupdocs.conversion.filetypes/cadfiletype/dgn) | File DGN, Design, adalah gambar yang dibuat dan didukung oleh aplikasi CAD seperti MicroStation dan Intergraph Interactive Graphics Design System. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/cad/dgn). |
| static readonly [Dwf](../../groupdocs.conversion.filetypes/cadfiletype/dwf) | Design Web Format (DWF) mewakili gambar 2D/3D dalam format terkompresi untuk melihat, meninjau, atau mencetak file desain. Ia berisi grafik dan teks sebagai bagian dari data desain serta mengurangi ukuran file karena format terkompresinya. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/cad/dwf). |
| static readonly [Dwfx](../../groupdocs.conversion.filetypes/cadfiletype/dwfx) | File DWFX adalah gambar 2D atau 3D yang dibuat dengan perangkat lunak Autodesk CAD. File ini disimpan dalam format DWFx, yang mirip dengan file . DWF, tetapi diformat menggunakan XML Paper Specification (XPS) milik Microsoft. |
| static readonly [Dwg](../../groupdocs.conversion.filetypes/cadfiletype/dwg) | File dengan ekstensi DWG mewakili file biner proprietari yang digunakan untuk menyimpan data desain 2D dan 3D. Seperti DXF, yang merupakan file ASCII, DWG mewakili format file biner untuk gambar CAD (Computer Aided Design). Pelajari lebih lanjut tentang format file ini [here](https://wiki.fileformat.com/cad/dwg). |
| static readonly [Dwt](../../groupdocs.conversion.filetypes/cadfiletype/dwt) | File DWT adalah file templat gambar AutoCAD yang digunakan sebagai awal untuk membuat gambar yang dapat disimpan sebagai file DWG. Pelajari lebih lanjut tentang format file ini [here](https://wiki.fileformat.com/cad/dwt). |
| static readonly [Dxf](../../groupdocs.conversion.filetypes/cadfiletype/dxf) | DXF, Drawing Interchange Format, atau Drawing Exchange Format, adalah representasi data bertag dari file gambar AutoCAD. Pelajari lebih lanjut tentang format file ini [here](https://wiki.fileformat.com/cad/dxf). |
| static readonly [Ifc](../../groupdocs.conversion.filetypes/cadfiletype/ifc) | File dengan ekstensi IFC mengacu pada format file Industry Foundation Classes (IFC) yang menetapkan standar internasional untuk mengimpor dan mengekspor objek bangunan serta propertinya. Format file ini menyediakan interoperabilitas antara berbagai aplikasi perangkat lunak. Pelajari lebih lanjut tentang format file ini [here](https://wiki.fileformat.com/cad/ifc). |
| static readonly [Igs](../../groupdocs.conversion.filetypes/cadfiletype/igs) | Format dokumen Igs |
| static readonly [Plt](../../groupdocs.conversion.filetypes/cadfiletype/plt) | Format file PLT adalah file plotter berbasis vektor yang diperkenalkan oleh Autodesk, Inc. dan berisi informasi untuk file CAD tertentu. Detail plotting memerlukan akurasi dan presisi dalam produksi, dan penggunaan file PLT menjamin hal ini karena semua gambar dicetak menggunakan garis bukan titik. Pelajari lebih lanjut tentang format file ini [here](https://wiki.fileformat.com/cad/plt). |
| static readonly [Stl](../../groupdocs.conversion.filetypes/cadfiletype/stl) | STL, singkatan dari stereolithrography, adalah format file yang dapat dipertukarkan yang mewakili geometri permukaan tiga dimensi. Format file ini digunakan dalam beberapa bidang seperti prototyping cepat, pencetakan 3D, dan manufaktur berbantuan komputer. Pelajari lebih lanjut tentang format file ini [here](https://wiki.fileformat.com/cad/stl). |

### Lihat Juga

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.conversion.dll -->
