---
title: "PresentationFileType"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Mendefinisikan format file Presentasi yang menyimpan koleksi catatan untuk menampung data presentasi seperti slide, bentuk, teks, animasi, video, audio, dan objek tersemat."
type: docs
weight: 22
url: /id/java/com.groupdocs.conversion.filetypes/presentationfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PresentationFileType extends FileType implements Serializable
```

Mendefinisikan format file Presentasi yang menyimpan koleksi catatan untuk menampung data presentasi seperti slide, bentuk, teks, animasi, video, audio, dan objek tersemat.
Menyertakan jenis file berikut:
[Odp](../../com.groupdocs.conversion.filetypes/presentationfiletype#Odp),
[Otp](../../com.groupdocs.conversion.filetypes/presentationfiletype#Otp),
[Pot](../../com.groupdocs.conversion.filetypes/presentationfiletype#Pot),
[Potm](../../com.groupdocs.conversion.filetypes/presentationfiletype#Potm),
[Potx](../../com.groupdocs.conversion.filetypes/presentationfiletype#Potx),
[Pps](../../com.groupdocs.conversion.filetypes/presentationfiletype#Pps),
[Ppsm](../../com.groupdocs.conversion.filetypes/presentationfiletype#Ppsm),
[Ppsx](../../com.groupdocs.conversion.filetypes/presentationfiletype#Ppsx),
[Ppt](../../com.groupdocs.conversion.filetypes/presentationfiletype#Ppt),
[Pptm](../../com.groupdocs.conversion.filetypes/presentationfiletype#Pptm),
[Pptx](../../com.groupdocs.conversion.filetypes/presentationfiletype#Pptx).
Pelajari lebih lanjut tentang format Presentasi [di sini](../https://wiki.fileformat.com/presentation).

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [PresentationFileType()](#PresentationFileType--) | Konstruktor serialisasi |
|
## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [Ppt](#Ppt) | File dengan ekstensi PPT mewakili file PowerPoint yang terdiri dari koleksi slide untuk ditampilkan sebagai SlideShow. |
|
|  | [Pps](#Pps) | PPS, PowerPoint Slide Show, file dibuat menggunakan Microsoft PowerPoint untuk tujuan Slide Show. |
|
|  | [Pptx](#Pptx) | File dengan ekstensi PPTX adalah file presentasi yang dibuat dengan aplikasi Microsoft PowerPoint yang populer. |
|
|  | [Ppsx](#Ppsx) | PPSX, Power Point Slide Show, file dibuat menggunakan Microsoft PowerPoint 2007 ke atas untuk tujuan Slide Show. |
|
|  | [Odp](#Odp) | File dengan ekstensi ODP mewakili format file presentasi yang digunakan oleh OpenOffice.org dalam standar OASISOpen. |
|
|  | [Otp](#Otp) | File dengan ekstensi .OTP mewakili file templat presentasi yang dibuat oleh aplikasi dalam format standar OASIS OpenDocument. |
|
|  | [Potx](#Potx) | File dengan ekstensi .POTX mewakili presentasi templat Microsoft PowerPoint yang dibuat dengan Microsoft PowerPoint 2007 ke atas. |
|
|  | [Pot](#Pot) | File dengan ekstensi .POT mewakili file templat Microsoft PowerPoint yang dibuat oleh versi PowerPoint 97-2003. |
|
|  | [Potm](#Potm) | File dengan ekstensi POTM adalah file templat Microsoft PowerPoint dengan dukungan untuk Makro. |
|
|  | [Pptm](#Pptm) | File dengan ekstensi PPTM adalah file Presentasi yang mendukung Makro yang dibuat dengan Microsoft PowerPoint 2007 atau versi yang lebih tinggi. |
|
|  | [Ppsm](#Ppsm) | File dengan ekstensi PPSM mewakili format file Slide Show yang mendukung Makro yang dibuat dengan Microsoft PowerPoint 2007 atau lebih tinggi. |
|
|  | [Fodp](#Fodp) | File dengan ekstensi FODP mewakili Presentasi OpenDocument Flat XML. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### PresentationFileType() {#PresentationFileType--}
```
public PresentationFileType()
```


Konstruktor serialisasi


### Ppt {#Ppt}
```
public static final PresentationFileType Ppt
```


File dengan ekstensi PPT mewakili file PowerPoint yang terdiri dari koleksi slide untuk ditampilkan sebagai SlideShow. File ini menggunakan Format File Biner yang dipakai oleh Microsoft PowerPoint 97-2003.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/presentation/ppt).


### Pps {#Pps}
```
public static final PresentationFileType Pps
```


PPS, PowerPoint Slide Show, file dibuat menggunakan Microsoft PowerPoint untuk tujuan Slide Show. Pembacaan dan pembuatan file PPS didukung oleh Microsoft PowerPoint 97-2003.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/presentation/pps).


### Pptx {#Pptx}
```
public static final PresentationFileType Pptx
```


File dengan ekstensi PPTX adalah file presentasi yang dibuat dengan aplikasi Microsoft PowerPoint yang populer. Tidak seperti versi sebelumnya dari format file presentasi PPT yang berbentuk biner, format PPTX berbasis pada format file presentasi Microsoft PowerPoint open XML.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/presentation/pptx).


### Ppsx {#Ppsx}
```
public static final PresentationFileType Ppsx
```


PPSX, Power Point Slide Show, file dibuat menggunakan Microsoft PowerPoint 2007 ke atas untuk tujuan Slide Show.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/presentation/ppsx).


### Odp {#Odp}
```
public static final PresentationFileType Odp
```


File dengan ekstensi ODP mewakili format file presentasi yang digunakan oleh OpenOffice.org dalam standar OASISOpen.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/presentation/odp).


### Otp {#Otp}
```
public static final PresentationFileType Otp
```


File dengan ekstensi .OTP mewakili file templat presentasi yang dibuat oleh aplikasi dalam format standar OASIS OpenDocument.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/presentation/otp).


### Potx {#Potx}
```
public static final PresentationFileType Potx
```


File dengan ekstensi .POTX mewakili presentasi templat Microsoft PowerPoint yang dibuat dengan Microsoft PowerPoint 2007 ke atas.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/presentation/potx).


### Pot {#Pot}
```
public static final PresentationFileType Pot
```


File dengan ekstensi .POT mewakili file templat Microsoft PowerPoint yang dibuat oleh versi PowerPoint 97-2003.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/presentation/pot).


### Potm {#Potm}
```
public static final PresentationFileType Potm
```


File dengan ekstensi POTM adalah file templat Microsoft PowerPoint dengan dukungan Makro. File POTM dibuat dengan PowerPoint 2007 atau yang lebih baru dan berisi pengaturan default yang dapat digunakan untuk membuat file presentasi lebih lanjut.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/presentation/potm).


### Pptm {#Pptm}
```
public static final PresentationFileType Pptm
```


File dengan ekstensi PPTM adalah file Presentasi yang mendukung Makro yang dibuat dengan Microsoft PowerPoint 2007 atau versi yang lebih tinggi.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/presentation/pptm).


### Ppsm {#Ppsm}
```
public static final PresentationFileType Ppsm
```


File dengan ekstensi PPSM mewakili format file Slide Show yang mendukung Makro yang dibuat dengan Microsoft PowerPoint 2007 atau lebih tinggi.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/presentation/ppsm).


### Fodp {#Fodp}
```
public static final PresentationFileType Fodp
```


File dengan ekstensi FODP mewakili Presentasi OpenDocument Flat XML. File presentasi disimpan dalam format OpenDocument, tetapi disimpan menggunakan format XML datar alih-alih kontainer .ZIP yang digunakan oleh file .ODP standar.


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
