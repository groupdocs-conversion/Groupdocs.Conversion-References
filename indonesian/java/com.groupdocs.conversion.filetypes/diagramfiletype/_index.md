---
title: "DiagramFileType"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Mendefinisikan dokumen Diagram."
type: docs
weight: 13
url: /id/java/com.groupdocs.conversion.filetypes/diagramfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class DiagramFileType extends FileType implements Serializable
```

Mendefinisikan dokumen Diagram. Menyertakan jenis-jenis berikut:
[Vdw](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vdw),
[Vdx](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vdx),
[Vsd](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vsd),
[Vsdm](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vsdm),
[Vsdx](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vsdx),
[Vss](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vss),
[Vssm](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vssm),
[Vssx](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vssx),
[Vst](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vst),
[Vstm](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vstm),
[Vstx](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vstx),
[Vsx](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vsx),
[Vtx](../../com.groupdocs.conversion.filetypes/diagramfiletype#Vtx).

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [DiagramFileType()](#DiagramFileType--) | Konstruktor serialisasi |
|
## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [Vsd](#Vsd) | File VSD adalah gambar yang dibuat dengan aplikasi Microsoft Visio untuk merepresentasikan berbagai objek grafis dan hubungan antar mereka. |
|
|  | [Vsdx](#Vsdx) | File dengan ekstensi .VSDX mewakili format file Microsoft Visio yang diperkenalkan sejak Microsoft Office 2013. |
|
|  | [Vss](#Vss) | VSS adalah file stensil yang dibuat dengan Microsoft Visio 2007 dan sebelumnya. |
|
|  | [Vst](#Vst) | File dengan ekstensi VST adalah file gambar vektor yang dibuat dengan Microsoft Visio dan berfungsi sebagai templat untuk membuat file selanjutnya. |
|
|  | [Vsx](#Vsx) | File dengan ekstensi .VSX mengacu pada stensil yang terdiri dari gambar dan bentuk yang digunakan untuk membuat diagram di Microsoft Visio. |
|
|  | [Vtx](#Vtx) | File dengan ekstensi VTX adalah templat gambar Microsoft Visio yang disimpan ke disk dalam format file XML. |
|
|  | [Vdw](#Vdw) | VDW adalah format file Visio Graphics Service yang menentukan aliran dan penyimpanan yang diperlukan untuk merender gambar Web. |
|
|  | [Vdx](#Vdx) | Setiap gambar atau diagram yang dibuat di Microsoft Visio, tetapi disimpan dalam format XML memiliki ekstensi .VDX. |
|
|  | [Vssx](#Vssx) | File dengan ekstensi .VSSX adalah stensil gambar yang dibuat dengan Microsoft Visio 2013 ke atas. |
|
|  | [Vstx](#Vstx) | File dengan ekstensi VSTX adalah file templat gambar yang dibuat dengan Microsoft Visio 2013 ke atas. |
|
|  | [Vsdm](#Vsdm) | File dengan ekstensi VSDM adalah file gambar yang dibuat dengan aplikasi Microsoft Visio yang mendukung makro. |
|
|  | [Vssm](#Vssm) | File dengan ekstensi .VSSM adalah file Stensil Microsoft Visio yang mendukung makro. |
|
|  | [Vstm](#Vstm) | File dengan ekstensi VSTM adalah file templat yang dibuat dengan Microsoft Visio yang mendukung makro. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### DiagramFileType() {#DiagramFileType--}
```
public DiagramFileType()
```


Konstruktor serialisasi


### Vsd {#Vsd}
```
public static final DiagramFileType Vsd
```


File VSD adalah gambar yang dibuat dengan aplikasi Microsoft Visio untuk merepresentasikan berbagai objek grafis dan hubungan antar mereka.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/image/vsd).


### Vsdx {#Vsdx}
```
public static final DiagramFileType Vsdx
```


File dengan ekstensi .VSDX mewakili format file Microsoft Visio yang diperkenalkan sejak Microsoft Office 2013. Format ini dikembangkan untuk menggantikan format file biner, .VSD, yang didukung oleh versi Microsoft Visio sebelumnya.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/image/vsdx).


### Vss {#Vss}
```
public static final DiagramFileType Vss
```


VSS adalah file stensil yang dibuat dengan Microsoft Visio 2007 dan sebelumnya. File stensil menyediakan objek gambar yang dapat dimasukkan ke dalam gambar .VSD Visio.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/image/vss).


### Vst {#Vst}
```
public static final DiagramFileType Vst
```


File dengan ekstensi VST adalah file gambar vektor yang dibuat dengan Microsoft Visio dan berfungsi sebagai templat untuk membuat file selanjutnya. File templat ini berada dalam format file biner dan berisi tata letak serta pengaturan default yang digunakan untuk membuat gambar Visio baru.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/image/vst).


### Vsx {#Vsx}
```
public static final DiagramFileType Vsx
```


File dengan ekstensi .VSX mengacu pada stensil yang terdiri dari gambar dan bentuk yang digunakan untuk membuat diagram di Microsoft Visio. File VSX disimpan dalam format file XML dan didukung hingga Visio 2013.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/image/vsx).


### Vtx {#Vtx}
```
public static final DiagramFileType Vtx
```


File dengan ekstensi VTX adalah templat gambar Microsoft Visio yang disimpan ke disk dalam format file XML. Templat ini bertujuan menyediakan file dengan pengaturan dasar yang dapat digunakan untuk membuat banyak file Visio dengan pengaturan yang sama.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/image/vtx).


### Vdw {#Vdw}
```
public static final DiagramFileType Vdw
```


VDW adalah format file Visio Graphics Service yang menentukan aliran dan penyimpanan yang diperlukan untuk merender gambar Web.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/web/vdw).


### Vdx {#Vdx}
```
public static final DiagramFileType Vdx
```


Setiap gambar atau diagram yang dibuat di Microsoft Visio, tetapi disimpan dalam format XML memiliki ekstensi .VDX. File XML gambar Visio dibuat dalam perangkat lunak Visio, yang dikembangkan oleh Microsoft.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/image/vdx).


### Vssx {#Vssx}
```
public static final DiagramFileType Vssx
```


File dengan ekstensi .VSSX adalah stensil gambar yang dibuat dengan Microsoft Visio 2013 ke atas. Format file VSSX dapat dibuka dengan Visio 2013 ke atas. File Visio dikenal karena representasi berbagai elemen gambar seperti kumpulan bentuk, penghubung, diagram alur, tata letak jaringan, diagram UML,
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/image/vssx).


### Vstx {#Vstx}
```
public static final DiagramFileType Vstx
```


File dengan ekstensi VSTX adalah file templat gambar yang dibuat dengan Microsoft Visio 2013 ke atas. File VSTX ini menyediakan titik awal untuk membuat gambar Visio, disimpan sebagai file .VSDX, dengan tata letak dan pengaturan default.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/image/vstx).


### Vsdm {#Vsdm}
```
public static final DiagramFileType Vsdm
```


File dengan ekstensi VSDM adalah file gambar yang dibuat dengan aplikasi Microsoft Visio yang mendukung makro. File VSDM adalah gambar OPC/XML yang mirip dengan VSDX, tetapi juga menyediakan kemampuan untuk menjalankan makro saat file dibuka.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/image/vsdm).


### Vssm {#Vssm}
```
public static final DiagramFileType Vssm
```


File dengan ekstensi .VSSM adalah file Stensil Microsoft Visio yang mendukung makro. File VSSM ketika dibuka memungkinkan menjalankan makro untuk mencapai pemformatan dan penempatan bentuk yang diinginkan dalam diagram.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/image/vssm).


### Vstm {#Vstm}
```
public static final DiagramFileType Vstm
```


File dengan ekstensi VSTM adalah file templat yang dibuat dengan Microsoft Visio yang mendukung makro. Tidak seperti file VSDX, file yang dibuat dari templat VSTM dapat menjalankan makro yang dikembangkan dalam kode Visual Basic for Applications (VBA).
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/image/vstm).


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
### getExcludedSourceTypes() {#getExcludedSourceTypes--}
```
public static final FileType[] getExcludedSourceTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static final FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
