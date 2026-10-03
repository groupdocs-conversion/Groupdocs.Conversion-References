---
title: "TxtLoadOptions"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Opsi untuk memuat dokumen Txt."
type: docs
weight: 34
url: /id/java/com.groupdocs.conversion.options.load/txtloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class TxtLoadOptions extends LoadOptions implements Serializable
```

Opsi untuk memuat dokumen Txt.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [TxtLoadOptions()](#TxtLoadOptions--) | Menginisialisasi instance baru dari kelas [TxtLoadOptions](../../com.groupdocs.conversion.options.load/txtloadoptions). |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDetectNumberingWithWhitespaces()](#getDetectNumberingWithWhitespaces--) | Mengizinkan penentuan bagaimana item daftar bernomor dikenali saat dokumen teks biasa dikonversi. |
|
|  | [setDetectNumberingWithWhitespaces(boolean value)](#setDetectNumberingWithWhitespaces-boolean-) | Mengizinkan penentuan bagaimana item daftar bernomor dikenali saat dokumen teks biasa dikonversi. |
|
|  | [getTrailingSpacesOptions()](#getTrailingSpacesOptions--) | Mendapatkan atau mengatur opsi preferensi penanganan spasi di akhir. |
|
|  | [setTrailingSpacesOptions(TxtTrailingSpacesOptions value)](#setTrailingSpacesOptions-com.groupdocs.conversion.options.load.TxtTrailingSpacesOptions-) | Mendapatkan atau mengatur opsi preferensi penanganan spasi di akhir. |
|
|  | [getLeadingSpacesOptions()](#getLeadingSpacesOptions--) | Mendapatkan atau mengatur opsi preferensi penanganan spasi di awal. |
|
|  | [setLeadingSpacesOptions(TxtLeadingSpacesOptions value)](#setLeadingSpacesOptions-com.groupdocs.conversion.options.load.TxtLeadingSpacesOptions-) | Mendapatkan atau mengatur opsi preferensi penanganan spasi di awal. |
|
|  | [getEncoding()](#getEncoding--) | Mendapatkan atau mengatur encoding yang akan digunakan saat memuat dokumen Txt. |
|
| [getEncodingInternal()](#getEncodingInternal--) |  |
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Mendapatkan atau mengatur encoding yang akan digunakan saat memuat dokumen Txt. |
|
### TxtLoadOptions() {#TxtLoadOptions--}
```
public TxtLoadOptions()
```


Menginisialisasi instance baru dari kelas [TxtLoadOptions](../../com.groupdocs.conversion.options.load/txtloadoptions).


### getFormat() {#getFormat--}
```
public WordProcessingFileType getFormat()
```


Jenis berkas dokumen input


**Returns:**
[WordProcessingFileType](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype)
### getDetectNumberingWithWhitespaces() {#getDetectNumberingWithWhitespaces--}
```
public final boolean getDetectNumberingWithWhitespaces()
```


Mengizinkan penentuan bagaimana item daftar bernomor dikenali saat dokumen teks biasa dikonversi.
Nilai default adalah true.

<br />

*** ** * ** ***

Jika opsi ini diatur ke false, algoritma pengenalan daftar mendeteksi paragraf daftar, ketika nomor daftar berakhir dengan
baik titik, kurung tutup, atau simbol bullet (seperti "\u2022", "\*", "-" atau "o").

Jika opsi ini diatur ke true, spasi juga digunakan sebagai pembatas nomor daftar:
algoritma pengenalan daftar untuk penomoran gaya Arab (1., 1.1.2.) menggunakan spasi dan simbol titik (".") sekaligus.

<br />



**Returns:**
boolean
### setDetectNumberingWithWhitespaces(boolean value) {#setDetectNumberingWithWhitespaces-boolean-}
```
public final void setDetectNumberingWithWhitespaces(boolean value)
```


Mengizinkan penentuan bagaimana item daftar bernomor dikenali saat dokumen teks biasa dikonversi.
Nilai default adalah true.

<br />

*** ** * ** ***

Jika opsi ini diatur ke false, algoritma pengenalan daftar mendeteksi paragraf daftar, ketika nomor daftar berakhir dengan
baik titik, kurung tutup, atau simbol bullet (seperti "\u2022", "\*", "-" atau "o").

Jika opsi ini diatur ke true, spasi juga digunakan sebagai pembatas nomor daftar:
algoritma pengenalan daftar untuk penomoran gaya Arab (1., 1.1.2.) menggunakan spasi dan simbol titik (".") sekaligus.

<br />



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getTrailingSpacesOptions() {#getTrailingSpacesOptions--}
```
public final TxtTrailingSpacesOptions getTrailingSpacesOptions()
```


Mendapatkan atau mengatur opsi preferensi penanganan spasi di akhir.
Nilai default adalah [TxtTrailingSpacesOptions.Trim](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions#Trim).


**Returns:**
[TxtTrailingSpacesOptions](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions)
### setTrailingSpacesOptions(TxtTrailingSpacesOptions value) {#setTrailingSpacesOptions-com.groupdocs.conversion.options.load.TxtTrailingSpacesOptions-}
```
public final void setTrailingSpacesOptions(TxtTrailingSpacesOptions value)
```


Mendapatkan atau mengatur opsi preferensi penanganan spasi di akhir.
Nilai default adalah [TxtTrailingSpacesOptions.Trim](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions#Trim).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [TxtTrailingSpacesOptions](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions) |  |

### getLeadingSpacesOptions() {#getLeadingSpacesOptions--}
```
public final TxtLeadingSpacesOptions getLeadingSpacesOptions()
```


Mendapatkan atau mengatur opsi preferensi penanganan spasi di awal.
Nilai default adalah [TxtLeadingSpacesOptions.ConvertToIndent](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions#ConvertToIndent).


**Returns:**
[TxtLeadingSpacesOptions](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions)
### setLeadingSpacesOptions(TxtLeadingSpacesOptions value) {#setLeadingSpacesOptions-com.groupdocs.conversion.options.load.TxtLeadingSpacesOptions-}
```
public final void setLeadingSpacesOptions(TxtLeadingSpacesOptions value)
```


Mendapatkan atau mengatur opsi preferensi penanganan spasi di awal.
Nilai default adalah [TxtLeadingSpacesOptions.ConvertToIndent](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions#ConvertToIndent).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [TxtLeadingSpacesOptions](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions) |  |

### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Mendapatkan atau mengatur enkoding yang akan digunakan saat memuat dokumen Txt. Bisa null. Nilai default adalah null.


**Returns:**
java.nio.charset.Charset
### getEncodingInternal() {#getEncodingInternal--}
```
public System.Text.Encoding getEncodingInternal()
```




**Returns:**
com.aspose.ms.System.Text.Encoding
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Mendapatkan atau mengatur enkoding yang akan digunakan saat memuat dokumen Txt. Bisa null. Nilai default adalah null.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.nio.charset.Charset |  |

