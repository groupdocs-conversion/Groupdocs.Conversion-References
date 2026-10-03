---
title: "DatabaseFileType"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Mendefinisikan dokumen CAD (Computer Aided Design) yang digunakan untuk format file grafis 3D dan dapat berisi desain 2D atau 3D."
type: docs
weight: 12
url: /id/java/com.groupdocs.conversion.filetypes/databasefiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class DatabaseFileType extends FileType implements Serializable
```

Mendefinisikan dokumen CAD (Computer Aided Design) yang digunakan untuk format file grafis 3D dan dapat berisi desain 2D atau 3D.
Mencakup tipe-tipe berikut:
[Nsf](../../com.groupdocs.conversion.filetypes/databasefiletype#Nsf),
[Log](../../com.groupdocs.conversion.filetypes/databasefiletype#Log),
[Sql](../../com.groupdocs.conversion.filetypes/databasefiletype#Sql),
Pelajari lebih lanjut tentang format CAD [di sini](../https://wiki.fileformat.com/cad).

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [DatabaseFileType()](#DatabaseFileType--) | Konstruktor serialisasi |
|
## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [Nsf](#Nsf) | File dengan ekstensi .nsf (Notes Storage Facility) adalah format file basis data yang digunakan oleh perangkat lunak IBM Notes, yang sebelumnya dikenal sebagai Lotus Notes. |
|
|  | [Log](#Log) | File dengan ekstensi .log berisi daftar teks biasa dengan cap waktu. |
|
|  | [Sql](#Sql) | File dengan ekstensi .sql adalah file Structured Query Language (SQL) yang berisi kode untuk bekerja dengan basis data relasional. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
### DatabaseFileType() {#DatabaseFileType--}
```
public DatabaseFileType()
```


Konstruktor serialisasi


### Nsf {#Nsf}
```
public static final DatabaseFileType Nsf
```


File dengan ekstensi .nsf (Notes Storage Facility) adalah format file basis data yang digunakan oleh perangkat lunak IBM Notes, yang sebelumnya dikenal sebagai Lotus Notes. Ia mendefinisikan skema untuk menyimpan berbagai jenis objek seperti email, janji, dokumen, formulir, dan tampilan. Pelajari lebih lanjut tentang format file ini [di sini](../https://docs.fileformat.com/database/nsf).


### Log {#Log}
```
public static final DatabaseFileType Log
```


File dengan ekstensi .log berisi daftar teks biasa dengan cap waktu. Biasanya, detail aktivitas tertentu dicatat oleh perangkat lunak atau sistem operasi untuk membantu pengembang atau pengguna melacak apa yang terjadi pada periode waktu tertentu. Pelajari lebih lanjut tentang format file ini [di sini](../https://docs.fileformat.com/database/log).


### Sql {#Sql}
```
public static final DatabaseFileType Sql
```


File dengan ekstensi .sql adalah file Structured Query Language (SQL) yang berisi kode untuk bekerja dengan basis data relasional. File ini digunakan untuk menulis pernyataan SQL untuk operasi CRUD (Create, Read, Update, and Delete) pada basis data. Pelajari lebih lanjut tentang format file ini [di sini](../https://docs.fileformat.com/database/sql).


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Menyiapkan opsi muat default untuk tipe file sumber


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
