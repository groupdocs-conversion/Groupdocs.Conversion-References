---
title: "JpegOptions"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Opsi untuk konversi ke tipe file Jpeg."
type: docs
weight: 20
url: /id/java/com.groupdocs.conversion.options.convert/jpegoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class JpegOptions extends ValueObject implements Serializable
```

Opsi untuk konversi ke tipe file Jpeg.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [JpegOptions()](#JpegOptions--) | Menginisialisasi instance baru dari kelas [JpegOptions](../../com.groupdocs.conversion.options.convert/jpegoptions). |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getQuality()](#getQuality--) | Kualitas gambar yang diinginkan. |
|
|  | [setQuality(int value)](#setQuality-int-) | Kualitas gambar yang diinginkan. |
|
|  | [getColorMode()](#getColorMode--) | Mode warna Jpg. |
|
|  | [setColorMode(JpgColorModes value)](#setColorMode-com.groupdocs.conversion.options.convert.JpgColorModes-) | Mode warna Jpg. |
|
|  | [getCompression()](#getCompression--) | Metode kompresi Jpg. |
|
|  | [setCompression(JpgCompressionMethods value)](#setCompression-com.groupdocs.conversion.options.convert.JpgCompressionMethods-) | Metode kompresi Jpg. |
|
### JpegOptions() {#JpegOptions--}
```
public JpegOptions()
```


Menginisialisasi instance baru dari kelas [JpegOptions](../../com.groupdocs.conversion.options.convert/jpegoptions).


### getQuality() {#getQuality--}
```
public final int getQuality()
```


Kualitas gambar yang diinginkan. Nilainya harus antara 0 dan 100. Nilai default adalah 100.


**Returns:**
int
### setQuality(int value) {#setQuality-int-}
```
public final void setQuality(int value)
```


Kualitas gambar yang diinginkan. Nilainya harus antara 0 dan 100. Nilai default adalah 100.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getColorMode() {#getColorMode--}
```
public final JpgColorModes getColorMode()
```


Mode warna Jpg.


**Returns:**
[JpgColorModes](../../com.groupdocs.conversion.options.convert/jpgcolormodes)
### setColorMode(JpgColorModes value) {#setColorMode-com.groupdocs.conversion.options.convert.JpgColorModes-}
```
public final void setColorMode(JpgColorModes value)
```


Mode warna Jpg.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [JpgColorModes](../../com.groupdocs.conversion.options.convert/jpgcolormodes) |  |

### getCompression() {#getCompression--}
```
public final JpgCompressionMethods getCompression()
```


Metode kompresi Jpg.


**Returns:**
[JpgCompressionMethods](../../com.groupdocs.conversion.options.convert/jpgcompressionmethods)
### setCompression(JpgCompressionMethods value) {#setCompression-com.groupdocs.conversion.options.convert.JpgCompressionMethods-}
```
public final void setCompression(JpgCompressionMethods value)
```


Metode kompresi Jpg.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [JpgCompressionMethods](../../com.groupdocs.conversion.options.convert/jpgcompressionmethods) |  |

