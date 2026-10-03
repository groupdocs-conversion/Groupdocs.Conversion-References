---
title: "EBookFileType"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Mendefinisikan dokumen CAD (Computer Aided Design) yang digunakan untuk format file grafis 3D dan dapat berisi desain 2D atau 3D."
type: docs
weight: 14
url: /id/java/com.groupdocs.conversion.filetypes/ebookfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class EBookFileType extends FileType implements Serializable
```

Mendefinisikan dokumen CAD (Computer Aided Design) yang digunakan untuk format file grafis 3D dan dapat berisi desain 2D atau 3D.
Mencakup tipe-tipe berikut:
[Epub](../../com.groupdocs.conversion.filetypes/ebookfiletype#Epub),
[Mobi](../../com.groupdocs.conversion.filetypes/ebookfiletype#Mobi),
[Azw3](../../com.groupdocs.conversion.filetypes/ebookfiletype#Azw3),
Pelajari lebih lanjut tentang format CAD [di sini](../https://wiki.fileformat.com/cad).

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [EBookFileType()](#EBookFileType--) | Konstruktor serialisasi |
|
## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [Epub](#Epub) | Ekstensi EPUB adalah format file e-book yang menyediakan format publikasi digital standar bagi penerbit dan konsumen. |
|
|  | [Mobi](#Mobi) | Format file MOBI adalah salah satu format file ebook yang paling banyak digunakan. |
|
|  | [Azw3](#Azw3) | AZW3, yang juga dikenal sebagai Kindle Format 8 (KF8), adalah versi modifikasi dari format file digital ebook AZW yang dikembangkan untuk perangkat Amazon Kindle. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### EBookFileType() {#EBookFileType--}
```
public EBookFileType()
```


Konstruktor serialisasi


### Epub {#Epub}
```
public static final EBookFileType Epub
```


Ekstensi EPUB adalah format file e-book yang menyediakan format publikasi digital standar bagi penerbit dan konsumen. Format ini kini sangat umum sehingga didukung oleh banyak e-reader dan aplikasi perangkat lunak. Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/ebook/epub).


### Mobi {#Mobi}
```
public static final EBookFileType Mobi
```


Format file MOBI adalah salah satu format file ebook yang paling banyak digunakan. Format ini merupakan peningkatan dari format OEB (Open Ebook Format) lama dan pernah digunakan sebagai format proprietari untuk Mobipocket Reader. Pelajari lebih lanjut tentang format file ini [di sini](../https://wiki.fileformat.com/ebook/mobi).


### Azw3 {#Azw3}
```
public static final EBookFileType Azw3
```


AZW3, yang juga dikenal sebagai Kindle Format 8 (KF8), adalah versi modifikasi dari format file digital ebook AZW yang dikembangkan untuk perangkat Amazon Kindle. Format ini merupakan peningkatan dari file AZW lama dan hanya digunakan pada perangkat Kindle Fire dengan kompatibilitas mundur untuk format file leluhur yaitu MOBI dan AZW. Pelajari lebih lanjut tentang format file ini [di sini](../https://docs.fileformat.com/ebook/azw3/).


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
