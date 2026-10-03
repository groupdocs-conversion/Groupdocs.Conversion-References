---
title: "PresentationConvertOptions"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Menjelaskan opsi untuk konversi ke tipe file Presentation."
type: docs
weight: 33
url: /id/java/com.groupdocs.conversion.options.convert/presentationconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable
```
public class PresentationConvertOptions extends CommonConvertOptions<PresentationFileType> implements Serializable
```

Menjelaskan opsi untuk konversi ke tipe file Presentation.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [PresentationConvertOptions()](#PresentationConvertOptions--) | Menginisialisasi instance baru dari kelas [PresentationConvertOptions](../../com.groupdocs.conversion.options.convert/presentationconvertoptions). |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getPassword()](#getPassword--) | Setel properti ini jika Anda ingin melindungi dokumen yang dikonversi dengan kata sandi. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Setel properti ini jika Anda ingin melindungi dokumen yang dikonversi dengan kata sandi. |
|
|  | [getZoom()](#getZoom--) | Menentukan tingkat zoom dalam persentase. |
|
|  | [setZoom(int value)](#setZoom-int-) | Menentukan tingkat zoom dalam persentase. |
|
### PresentationConvertOptions() {#PresentationConvertOptions--}
```
public PresentationConvertOptions()
```


Menginisialisasi instance baru dari kelas [PresentationConvertOptions](../../com.groupdocs.conversion.options.convert/presentationconvertoptions).


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Setel properti ini jika Anda ingin melindungi dokumen yang dikonversi dengan kata sandi.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Setel properti ini jika Anda ingin melindungi dokumen yang dikonversi dengan kata sandi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getZoom() {#getZoom--}
```
public final int getZoom()
```


Menentukan tingkat zoom dalam persentase. Defaultnya adalah 100.
Zoom default didukung hingga Microsoft Powerpoint 2010. Mulai dari Microsoft Powerpoint 2013, zoom default tidak lagi diatur ke dokumen, melainkan tampaknya menggunakan faktor zoom dari dokumen terakhir yang dibuka.


**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


Menentukan tingkat zoom dalam persentase. Defaultnya adalah 100.
Zoom default didukung hingga Microsoft Powerpoint 2010. Mulai dari Microsoft Powerpoint 2013, zoom default tidak lagi diatur ke dokumen, melainkan tampaknya menggunakan faktor zoom dari dokumen terakhir yang dibuka.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

