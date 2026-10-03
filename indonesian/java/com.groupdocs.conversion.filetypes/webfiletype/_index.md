---
title: "WebFileType"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Mendefinisikan dokumen Web."
type: docs
weight: 27
url: /id/java/com.groupdocs.conversion.filetypes/webfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class WebFileType extends FileType implements Serializable
```

Mendefinisikan dokumen Web.
Mencakup tipe-tipe berikut:
[Xml](../../com.groupdocs.conversion.filetypes/webfiletype#Xml),
[Json](../../com.groupdocs.conversion.filetypes/webfiletype#Json),
[Html](../../com.groupdocs.conversion.filetypes/webfiletype#Html),
[Htm](../../com.groupdocs.conversion.filetypes/webfiletype#Htm),
[Mht](../../com.groupdocs.conversion.filetypes/webfiletype#Mht),
[Mhtml](../../com.groupdocs.conversion.filetypes/webfiletype#Mhtml),
[Chm](../../com.groupdocs.conversion.filetypes/webfiletype#Chm),
Pelajari lebih lanjut tentang format web [di sini](../https://wiki.fileformat.com/web).

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [WebFileType()](#WebFileType--) | Konstruktor serialisasi |
|
## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [Xml](#Xml) | XML merupakan singkatan dari Extensible Markup Language yang mirip dengan HTML tetapi berbeda dalam penggunaan tag untuk mendefinisikan objek. |
|
|  | [Json](#Json) | JSON (JavaScript Object Notation) adalah format file standar terbuka untuk berbagi data yang menggunakan teks yang dapat dibaca manusia untuk menyimpan dan mentransmisikan data. |
|
|  | [Html](#Html) | HTML (Hyper Text Markup Language) adalah ekstensi untuk halaman web yang dibuat untuk ditampilkan di peramban. |
|
|  | [Htm](#Htm) | HTM (Hyper Text Markup Language) adalah ekstensi untuk halaman web yang dibuat untuk ditampilkan di peramban. |
|
|  | [Mht](#Mht) | File dengan ekstensi MHTML mewakili format arsip halaman web yang dapat dibuat oleh sejumlah aplikasi berbeda. |
|
|  | [Mhtml](#Mhtml) | File dengan ekstensi MHTML mewakili format arsip halaman web yang dapat dibuat oleh sejumlah aplikasi berbeda. |
|
|  | [Chm](#Chm) | Format file CHM mewakili file bantuan HTML Microsoft yang terdiri dari kumpulan halaman HTML. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### WebFileType() {#WebFileType--}
```
public WebFileType()
```


Konstruktor serialisasi


### Xml {#Xml}
```
public static final WebFileType Xml
```


XML merupakan singkatan dari Extensible Markup Language yang mirip dengan HTML tetapi berbeda dalam penggunaan tag untuk mendefinisikan objek. Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/web/xml).


### Json {#Json}
```
public static final WebFileType Json
```


JSON (JavaScript Object Notation) adalah format file standar terbuka untuk berbagi data yang menggunakan teks yang dapat dibaca manusia untuk menyimpan dan mentransmisikan data. Pelajari lebih lanjut tentang format file ini [di sini](../https://docs.fileformat.com/web/json).


### Html {#Html}
```
public static final WebFileType Html
```


HTML (Hyper Text Markup Language) adalah ekstensi untuk halaman web yang dibuat untuk ditampilkan di peramban. Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/web/html).


### Htm {#Htm}
```
public static final WebFileType Htm
```


HTM (Hyper Text Markup Language) adalah ekstensi untuk halaman web yang dibuat untuk ditampilkan di peramban. Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/web/html).


### Mht {#Mht}
```
public static final WebFileType Mht
```


File dengan ekstensi MHTML mewakili format arsip halaman web yang dapat dibuat oleh sejumlah aplikasi berbeda. Format ini dikenal sebagai format arsip karena menyimpan kode HTML web dan sumber daya terkait dalam satu file. Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/web/mhtml).


### Mhtml {#Mhtml}
```
public static final WebFileType Mhtml
```


File dengan ekstensi MHTML mewakili format arsip halaman web yang dapat dibuat oleh sejumlah aplikasi berbeda. Format ini dikenal sebagai format arsip karena menyimpan kode HTML web dan sumber daya terkait dalam satu file. Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/web/mhtml).


### Chm {#Chm}
```
public static final WebFileType Chm
```


Format file CHM mewakili file bantuan HTML Microsoft yang terdiri dari kumpulan halaman HTML. Ini menyediakan indeks untuk mengakses topik dengan cepat dan navigasi ke bagian-bagian berbeda dari dokumen bantuan. Pelajari lebih lanjut tentang format file ini [di sini](../https://docs.fileformat.com/web/chm).


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
