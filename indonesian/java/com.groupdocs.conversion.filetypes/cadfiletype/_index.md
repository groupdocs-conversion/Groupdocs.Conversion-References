---
title: "CadFileType"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Mendefinisikan dokumen CAD (Computer Aided Design) yang digunakan untuk format file grafis 3D dan dapat berisi desain 2D atau 3D."
type: docs
weight: 11
url: /id/java/com.groupdocs.conversion.filetypes/cadfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class CadFileType extends FileType implements Serializable
```

Mendefinisikan dokumen CAD (Computer Aided Design) yang digunakan untuk format file grafis 3D dan dapat berisi desain 2D atau 3D.
Mencakup tipe-tipe berikut:
[Dgn](../../com.groupdocs.conversion.filetypes/cadfiletype#Dgn),
[Dwf](../../com.groupdocs.conversion.filetypes/cadfiletype#Dwf),
[Dwg](../../com.groupdocs.conversion.filetypes/cadfiletype#Dwg),
[Dwt](../../com.groupdocs.conversion.filetypes/cadfiletype#Dwt),
[Dxf](../../com.groupdocs.conversion.filetypes/cadfiletype#Dxf),
[Ifc](../../com.groupdocs.conversion.filetypes/cadfiletype#Ifc),
[Igs](../../com.groupdocs.conversion.filetypes/cadfiletype#Igs),
[Plt](../../com.groupdocs.conversion.filetypes/cadfiletype#Plt),
[Stl](../../com.groupdocs.conversion.filetypes/cadfiletype#Stl).
[Cf2](../../com.groupdocs.conversion.filetypes/cadfiletype#Cf2).
[Dwfx](../../com.groupdocs.conversion.filetypes/cadfiletype#Dwfx).
Pelajari lebih lanjut tentang format CAD [di sini](../https://wiki.fileformat.com/cad).

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [CadFileType()](#CadFileType--) | Konstruktor serialisasi |
|
## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [Dxf](#Dxf) | DXF, Drawing Interchange Format, atau Drawing Exchange Format, adalah representasi data bertag dari file gambar AutoCAD. |
|
|  | [Dwg](#Dwg) | File dengan ekstensi DWG merupakan file biner proprietari yang digunakan untuk menyimpan data desain 2D dan 3D. |
|
|  | [Dgn](#Dgn) | DGN, file desain, adalah gambar yang dibuat dan didukung oleh aplikasi CAD seperti MicroStation dan Intergraph Interactive Graphics Design System. |
|
|  | [Dwf](#Dwf) | Design Web Format (DWF) mewakili gambar 2D/3D dalam format terkompresi untuk melihat, meninjau, atau mencetak file desain. |
|
|  | [Stl](#Stl) | STL, singkatan dari stereolithography, adalah format file yang dapat dipertukarkan yang mewakili geometri permukaan tiga dimensi. |
|
|  | [Ifc](#Ifc) | File dengan ekstensi IFC mengacu pada format file Industry Foundation Classes (IFC) yang menetapkan standar internasional untuk mengimpor dan mengekspor objek bangunan serta propertinya. |
|
|  | [Plt](#Plt) | Format file PLT adalah file plotter berbasis vektor yang diperkenalkan oleh Autodesk, Inc. |
|
|  | [Igs](#Igs) | Format dokumen Igs |
|
|  | [Dwt](#Dwt) | File DWT adalah file templat gambar AutoCAD yang digunakan sebagai awal untuk membuat gambar yang dapat disimpan sebagai file DWG. |
|
|  | [Dwfx](#Dwfx) | File DWFX adalah gambar 2D atau 3D yang dibuat dengan perangkat lunak Autodesk CAD. |
|
|  | [Cf2](#Cf2) | File Format Umum. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### CadFileType() {#CadFileType--}
```
public CadFileType()
```


Konstruktor serialisasi


### Dxf {#Dxf}
```
public static final CadFileType Dxf
```


DXF, Drawing Interchange Format, atau Drawing Exchange Format, adalah representasi data bertag dari file gambar AutoCAD.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/cad/dxf).


### Dwg {#Dwg}
```
public static final CadFileType Dwg
```


File dengan ekstensi DWG merupakan file biner proprietari yang digunakan untuk menyimpan data desain 2D dan 3D. Seperti DXF, yang merupakan file ASCII, DWG mewakili format file biner untuk gambar CAD (Computer Aided Design).
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/cad/dwg)


### Dgn {#Dgn}
```
public static final CadFileType Dgn
```


DGN, file desain, adalah gambar yang dibuat dan didukung oleh aplikasi CAD seperti MicroStation dan Intergraph Interactive Graphics Design System.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/cad/dgn).


### Dwf {#Dwf}
```
public static final CadFileType Dwf
```


Design Web Format (DWF) mewakili gambar 2D/3D dalam format terkompresi untuk melihat, meninjau, atau mencetak file desain. Ia berisi grafik dan teks sebagai bagian dari data desain dan mengurangi ukuran file karena format terkompresinya.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/cad/dwf).


### Stl {#Stl}
```
public static final CadFileType Stl
```


STL, singkatan dari stereolithrography, adalah format file yang dapat dipertukarkan yang mewakili geometri permukaan tiga dimensi. Format file ini digunakan dalam beberapa bidang seperti prototipe cepat, pencetakan 3D, dan manufaktur berbantuan komputer.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/cad/stl).


### Ifc {#Ifc}
```
public static final CadFileType Ifc
```


File dengan ekstensi IFC mengacu pada format file Industry Foundation Classes (IFC) yang menetapkan standar internasional untuk mengimpor dan mengekspor objek bangunan serta propertinya. Format file ini menyediakan interoperabilitas antara berbagai aplikasi perangkat lunak.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/cad/ifc).


### Plt {#Plt}
```
public static final CadFileType Plt
```


Format file PLT adalah file plotter berbasis vektor yang diperkenalkan oleh Autodesk, Inc. dan berisi informasi untuk file CAD tertentu. Detail plotting memerlukan akurasi dan presisi dalam produksi, dan penggunaan file PLT menjamin hal ini karena semua gambar dicetak menggunakan garis, bukan titik.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/cad/plt).


### Igs {#Igs}
```
public static final CadFileType Igs
```


Format dokumen Igs


### Dwt {#Dwt}
```
public static final CadFileType Dwt
```


File DWT adalah file templat gambar AutoCAD yang digunakan sebagai awal untuk membuat gambar yang dapat disimpan sebagai file DWG.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/cad/dwt).


### Dwfx {#Dwfx}
```
public static final CadFileType Dwfx
```


File DWFX adalah gambar 2D atau 3D yang dibuat dengan perangkat lunak Autodesk CAD. File ini disimpan dalam format DWFx, yang mirip dengan file .DWF, tetapi diformat menggunakan XML Paper Specification (XPS) milik Microsoft.


### Cf2 {#Cf2}
```
public static final CadFileType Cf2
```


File Common File Format. File CAD yang berisi desain paket 3D atau data model lainnya; dapat diproses dan dipotong oleh mesin CAD/CAM, seperti perangkat pemotong die.


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Menyiapkan opsi muat default untuk tipe file sumber


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Menyiapkan opsi konversi default untuk tipe file


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
