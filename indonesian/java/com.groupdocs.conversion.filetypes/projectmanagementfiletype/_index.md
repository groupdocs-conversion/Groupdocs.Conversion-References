---
title: "ProjectManagementFileType"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Mendefinisikan format file Proyek yang dibuat oleh perangkat lunak Manajemen Proyek seperti Microsoft Project, Primavera P6, dll."
type: docs
weight: 23
url: /id/java/com.groupdocs.conversion.filetypes/projectmanagementfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)
```
public final class ProjectManagementFileType extends FileType
```

Mendefinisikan format file Proyek yang dibuat oleh perangkat lunak Manajemen Proyek seperti Microsoft Project, Primavera P6, dll. File proyek adalah kumpulan tugas, sumber daya, dan penjadwalannya untuk menghasilkan output yang terukur berupa produk atau layanan.
Dokumen manajemen proyek. Mencakup jenis file berikut:
[Mpp](../../com.groupdocs.conversion.filetypes/projectmanagementfiletype#Mpp),
[Mpt](../../com.groupdocs.conversion.filetypes/projectmanagementfiletype#Mpt),
[Mpx](../../com.groupdocs.conversion.filetypes/projectmanagementfiletype#Mpx).
Pelajari lebih lanjut tentang format Manajemen Proyek [di sini](../https://wiki.fileformat.com/project-management).

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [ProjectManagementFileType()](#ProjectManagementFileType--) | Konstruktor serialisasi |
|
## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [Mpt](#Mpt) | File templat Microsoft Project, berisi informasi dasar dan struktur bersama dengan pengaturan dokumen untuk membuat file .MPP. |
|
|  | [Mpp](#Mpp) | MPP adalah file data Microsoft Project yang menyimpan informasi terkait manajemen proyek secara terintegrasi. |
|
|  | [Mpx](#Mpx) | Microsoft Exchange File Format, adalah format file ASCII untuk mentransfer informasi proyek antara Microsoft Project (MSP) dan aplikasi lain yang mendukung format file MPX seperti Primavera Project Planner, Sciforma, dan Timerline Precision Estimating. |
|
|  | [Xer](#Xer) | Format file XER adalah format file proyek proprietari yang digunakan oleh aplikasi perencanaan dan manajemen proyek Primavera P6. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### ProjectManagementFileType() {#ProjectManagementFileType--}
```
public ProjectManagementFileType()
```


Konstruktor serialisasi


### Mpt {#Mpt}
```
public static final ProjectManagementFileType Mpt
```


File templat Microsoft Project, berisi informasi dasar dan struktur bersama dengan pengaturan dokumen untuk membuat file .MPP.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/project-management/mpt).


### Mpp {#Mpp}
```
public static final ProjectManagementFileType Mpp
```


MPP adalah file data Microsoft Project yang menyimpan informasi terkait manajemen proyek secara terintegrasi.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/project-management/mpp).


### Mpx {#Mpx}
```
public static final ProjectManagementFileType Mpx
```


Microsoft Exchange File Format, adalah format file ASCII untuk mentransfer informasi proyek antara Microsoft Project (MSP) dan aplikasi lain yang mendukung format file MPX seperti Primavera Project Planner, Sciforma, dan Timerline Precision Estimating.
Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/project-management/mpx).


### Xer {#Xer}
```
public static final ProjectManagementFileType Xer
```


Format file XER adalah format file proyek proprietari yang digunakan oleh aplikasi perencanaan dan manajemen proyek Primavera P6.
Pelajari lebih lanjut tentang format file ini [di sini](../https://docs.fileformat.com/project-management/xer).


### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Menyiapkan opsi konversi default untuk tipe file


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static final FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
