---
title: "PdfOptimizationOptions"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Mendefinisikan opsi optimasi Pdf."
type: docs
weight: 29
url: /id/java/com.groupdocs.conversion.options.convert/pdfoptimizationoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PdfOptimizationOptions extends ValueObject implements Serializable
```

Mendefinisikan opsi optimasi Pdf.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [PdfOptimizationOptions()](#PdfOptimizationOptions--) | Menginisialisasi instance baru dari kelas [PdfOptimizationOptions](../../com.groupdocs.conversion.options.convert/pdfoptimizationoptions). |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getLinkDuplicateStreams()](#getLinkDuplicateStreams--) | Tautkan aliran duplikat |
|
|  | [setLinkDuplicateStreams(boolean value)](#setLinkDuplicateStreams-boolean-) | Tautkan aliran duplikat |
|
|  | [getRemoveUnusedObjects()](#getRemoveUnusedObjects--) | Hapus objek yang tidak terpakai |
|
|  | [setRemoveUnusedObjects(boolean value)](#setRemoveUnusedObjects-boolean-) | Hapus objek yang tidak terpakai |
|
|  | [getRemoveUnusedStreams()](#getRemoveUnusedStreams--) | Hapus aliran yang tidak terpakai |
|
|  | [setRemoveUnusedStreams(boolean value)](#setRemoveUnusedStreams-boolean-) | Hapus aliran yang tidak terpakai |
|
|  | [getCompressImages()](#getCompressImages--) | Jika CompressImages diatur ke |
true
, semua gambar dalam dokumen akan dikompres ulang.
|
|  | [setCompressImages(boolean value)](#setCompressImages-boolean-) | Jika CompressImages diatur ke |
true
, semua gambar dalam dokumen akan dikompres ulang.
|
|  | [getImageQuality()](#getImageQuality--) | Nilai dalam persen dimana 100% berarti kualitas dan ukuran gambar tidak berubah. |
|
|  | [setImageQuality(int value)](#setImageQuality-int-) | Nilai dalam persen dimana 100% berarti kualitas dan ukuran gambar tidak berubah. |
|
|  | [getUnembedFonts()](#getUnembedFonts--) | Jadikan font tidak disematkan jika diatur ke true |
|
|  | [setUnembedFonts(boolean value)](#setUnembedFonts-boolean-) | Jadikan font tidak disematkan jika diatur ke true |
|
| [getFontSubsetStrategy()](#getFontSubsetStrategy--) |  |
|  | [setFontSubsetStrategy(PdfFontSubsetStrategy fontSubsetStrategy)](#setFontSubsetStrategy-com.groupdocs.conversion.options.convert.PdfFontSubsetStrategy-) | Atur strategi subset font |
|
### PdfOptimizationOptions() {#PdfOptimizationOptions--}
```
public PdfOptimizationOptions()
```


Menginisialisasi instance baru dari kelas [PdfOptimizationOptions](../../com.groupdocs.conversion.options.convert/pdfoptimizationoptions).


### getLinkDuplicateStreams() {#getLinkDuplicateStreams--}
```
public final boolean getLinkDuplicateStreams()
```


Tautkan aliran duplikat


**Returns:**
boolean
### setLinkDuplicateStreams(boolean value) {#setLinkDuplicateStreams-boolean-}
```
public final void setLinkDuplicateStreams(boolean value)
```


Tautkan aliran duplikat


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getRemoveUnusedObjects() {#getRemoveUnusedObjects--}
```
public final boolean getRemoveUnusedObjects()
```


Hapus objek yang tidak terpakai


**Returns:**
boolean
### setRemoveUnusedObjects(boolean value) {#setRemoveUnusedObjects-boolean-}
```
public final void setRemoveUnusedObjects(boolean value)
```


Hapus objek yang tidak terpakai


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getRemoveUnusedStreams() {#getRemoveUnusedStreams--}
```
public final boolean getRemoveUnusedStreams()
```


Hapus aliran yang tidak terpakai


**Returns:**
boolean
### setRemoveUnusedStreams(boolean value) {#setRemoveUnusedStreams-boolean-}
```
public final void setRemoveUnusedStreams(boolean value)
```


Hapus aliran yang tidak terpakai


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getCompressImages() {#getCompressImages--}
```
public final boolean getCompressImages()
```


Jika CompressImages diatur ke
true
, semua gambar dalam dokumen dikompres ulang. Kompresi ditentukan oleh properti ImageQuality.


**Returns:**
boolean
### setCompressImages(boolean value) {#setCompressImages-boolean-}
```
public final void setCompressImages(boolean value)
```


Jika CompressImages diatur ke
true
, semua gambar dalam dokumen dikompres ulang. Kompresi ditentukan oleh properti ImageQuality.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getImageQuality() {#getImageQuality--}
```
public final int getImageQuality()
```


Nilai dalam persen dimana 100% berarti kualitas dan ukuran gambar tidak berubah. Untuk mengurangi ukuran gambar, atur properti ini menjadi kurang dari 100.


**Returns:**
int
### setImageQuality(int value) {#setImageQuality-int-}
```
public final void setImageQuality(int value)
```


Nilai dalam persen dimana 100% berarti kualitas dan ukuran gambar tidak berubah. Untuk mengurangi ukuran gambar, atur properti ini menjadi kurang dari 100.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getUnembedFonts() {#getUnembedFonts--}
```
public final boolean getUnembedFonts()
```


Jadikan font tidak disematkan jika diatur ke true


**Returns:**
boolean
### setUnembedFonts(boolean value) {#setUnembedFonts-boolean-}
```
public final void setUnembedFonts(boolean value)
```


Jadikan font tidak disematkan jika diatur ke true


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getFontSubsetStrategy() {#getFontSubsetStrategy--}
```
public PdfFontSubsetStrategy getFontSubsetStrategy()
```




**Returns:**
[PdfFontSubsetStrategy](../../com.groupdocs.conversion.options.convert/pdffontsubsetstrategy)
### setFontSubsetStrategy(PdfFontSubsetStrategy fontSubsetStrategy) {#setFontSubsetStrategy-com.groupdocs.conversion.options.convert.PdfFontSubsetStrategy-}
```
public void setFontSubsetStrategy(PdfFontSubsetStrategy fontSubsetStrategy)
```


Atur strategi subset font


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontSubsetStrategy | [PdfFontSubsetStrategy](../../com.groupdocs.conversion.options.convert/pdffontsubsetstrategy) |  |

