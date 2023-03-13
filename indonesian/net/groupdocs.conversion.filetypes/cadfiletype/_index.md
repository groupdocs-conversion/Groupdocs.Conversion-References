---
title: CadFileType
second_title: GroupDocs.Konversi untuk Referensi .NET API
description: Menentukan dokumen CAD Computer Aided Design yang digunakan untuk format file grafik 3D dan mungkin berisi desain 2D atau 3D. Termasuk jenis berikut Cf2./cadfiletype/cf2Dgn./cadfiletype/dgn  Dwf./cadfiletype/dwf  Dwfx./cadfiletype/dwfxDwg./cadfiletype/dwg  Dwt./cadfiletype/dwt  Dxf./cadfiletype/dxf  Ifc./cadfiletype/ifc  Igs./cadfiletype/igs  Plt./cadfiletype/plt  Stl./cadfiletype/stl . Pelajari lebih lanjut tentang format CADDi Sinihttps//wiki.fileformat.com/cad .
type: docs
weight: 860
url: /id/net/groupdocs.conversion.filetypes/cadfiletype/
---
## CadFileType class

Menentukan dokumen CAD (Computer Aided Design) yang digunakan untuk format file grafik 3D dan mungkin berisi desain 2D atau 3D. Termasuk jenis berikut: [`Cf2`](./cf2)[`Dgn`](./dgn) , [`Dwf`](./dwf) , [`Dwfx`](./dwfx)[`Dwg`](./dwg) , [`Dwt`](./dwt) , [`Dxf`](./dxf) , [`Ifc`](./ifc) , [`Igs`](./igs) , [`Plt`](./plt) , [`Stl`](./stl) . Pelajari lebih lanjut tentang format CAD[Di Sini](https://wiki.fileformat.com/cad) .

```csharp
public sealed class CadFileType : FileType
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [CadFileType](cadfiletype)() | Konstruktor serialisasi |

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
| static readonly [Cf2](../../groupdocs.conversion.filetypes/cadfiletype/cf2) | File Format File Umum. File CAD yang berisi desain paket 3D atau data model lainnya; dapat diproses dan dipotong oleh mesin CAD/CAM, seperti alat pemotong mati. |
| static readonly [Dgn](../../groupdocs.conversion.filetypes/cadfiletype/dgn) | DGN, Desain, file adalah gambar yang dibuat oleh dan didukung oleh aplikasi CAD seperti MicroStation dan Intergraph Interactive Graphics Design System. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/cad/dgn) . |
| static readonly [Dwf](../../groupdocs.conversion.filetypes/cadfiletype/dwf) | Format Web Desain (DWF) mewakili gambar 2D/3D dalam format terkompresi untuk melihat, meninjau, atau mencetak file desain. Ini berisi grafik dan teks sebagai bagian dari data desain dan mengurangi ukuran file karena formatnya yang terkompresi. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/cad/dwf) . |
| static readonly [Dwfx](../../groupdocs.conversion.filetypes/cadfiletype/dwfx) | File DWFX adalah gambar 2D atau 3D yang dibuat dengan perangkat lunak Autodesk CAD. Itu disimpan dalam format DWFx, yang mirip dengan file . DWF, tetapi diformat menggunakan Spesifikasi Kertas XML Microsoft (XPS). |
| static readonly [Dwg](../../groupdocs.conversion.filetypes/cadfiletype/dwg) | File dengan ekstensi DWG mewakili file biner eksklusif yang digunakan untuk memuat data desain 2D dan 3D. Seperti DXF, yang merupakan file ASCII, DWG mewakili format file biner untuk gambar CAD (Computer Aided Design). Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/cad/dwg) . |
| static readonly [Dwt](../../groupdocs.conversion.filetypes/cadfiletype/dwt) | File DWT adalah file template gambar AutoCAD yang digunakan sebagai starter untuk membuat gambar yang dapat disimpan sebagai file DWG. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/cad/dwt) . |
| static readonly [Dxf](../../groupdocs.conversion.filetypes/cadfiletype/dxf) | DXF, Drawing Interchange Format, atau Drawing Exchange Format, adalah representasi data yang ditandai dari file gambar AutoCAD. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/cad/dxf) . |
| static readonly [Ifc](../../groupdocs.conversion.filetypes/cadfiletype/ifc) | File dengan ekstensi IFC mengacu pada format file Industry Foundation Classes (IFC) yang menetapkan standar internasional untuk mengimpor dan mengekspor objek bangunan dan propertinya. Format file ini menyediakan interoperabilitas antara aplikasi perangkat lunak yang berbeda. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/cad/ifc) . |
| static readonly [Igs](../../groupdocs.conversion.filetypes/cadfiletype/igs) | Format dokumen igs |
| static readonly [Plt](../../groupdocs.conversion.filetypes/cadfiletype/plt) | Format file PLT adalah file plotter berbasis vektor yang diperkenalkan oleh Autodesk, Inc. dan berisi informasi untuk file CAD tertentu. Detail plot membutuhkan akurasi dan presisi dalam produksi, dan penggunaan file PLT menjamin ini karena semua gambar dicetak menggunakan garis, bukan titik. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/cad/plt) . |
| static readonly [Stl](../../groupdocs.conversion.filetypes/cadfiletype/stl) | STL, singkatan dari stereolihrography, adalah format file yang dapat dipertukarkan yang mewakili geometri permukaan 3 dimensi. Format file menemukan penggunaannya di beberapa bidang seperti pembuatan prototipe cepat, pencetakan 3D, dan pembuatan dengan bantuan komputer. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/cad/stl) . |

### Lihat juga

* class [FileType](../filetype)
* ruang nama [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* perakitan [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
