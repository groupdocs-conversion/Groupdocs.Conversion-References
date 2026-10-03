---
title: "PublisherFileType"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Mendefinisikan dokumen Publisher."
type: docs
weight: 24
url: /id/java/com.groupdocs.conversion.filetypes/publisherfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PublisherFileType extends FileType implements Serializable
```

Mendefinisikan dokumen Publisher.
Mencakup tipe-tipe berikut:
[Pub](../../com.groupdocs.conversion.filetypes/publisherfiletype#Pub),
Pelajari lebih lanjut tentang format Font [di sini](../https://wiki.fileformat.com/publisher).

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [PublisherFileType()](#PublisherFileType--) | Konstruktor serialisasi |
|
## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [Pub](#Pub) | File PUB adalah format file dokumen Microsoft Publisher. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### PublisherFileType() {#PublisherFileType--}
```
public PublisherFileType()
```


Konstruktor serialisasi


### Pub {#Pub}
```
public static final PublisherFileType Pub
```


File PUB adalah format file dokumen Microsoft Publisher. File ini digunakan untuk membuat berbagai jenis dokumen tata letak desain seperti buletin, selebaran, brosur, kartu pos, dll. File PUB dapat berisi teks, gambar raster, dan vektor. Pelajari lebih lanjut tentang format file ini [di sini](../https://docs.fileformat.com/publisher/pub/).


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Menyiapkan opsi muat default untuk tipe file sumber


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getExcludedSourceTypes() {#getExcludedSourceTypes--}
```
public static FileType[] getExcludedSourceTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
