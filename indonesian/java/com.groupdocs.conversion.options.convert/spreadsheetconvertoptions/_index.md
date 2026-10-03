---
title: "SpreadsheetConvertOptions"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Opsi untuk konversi ke tipe file Spreadsheet."
type: docs
weight: 40
url: /id/java/com.groupdocs.conversion.options.convert/spreadsheetconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable
```
public class SpreadsheetConvertOptions extends CommonConvertOptions<SpreadsheetFileType> implements Serializable
```

Opsi untuk konversi ke tipe file Spreadsheet.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [SpreadsheetConvertOptions()](#SpreadsheetConvertOptions--) | Menginisialisasi instance baru dari kelas [SpreadsheetConvertOptions](../../com.groupdocs.conversion.options.convert/spreadsheetconvertoptions). |
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
|  | [getSeparator()](#getSeparator--) | Menentukan pemisah yang akan digunakan saat mengonversi ke format terdelimit. |
|
| [setSeparator(char separator)](#setSeparator-char-) |  |
| [setFormat(FileType value)](#setFormat-com.groupdocs.conversion.filetypes.FileType-) |  |
### SpreadsheetConvertOptions() {#SpreadsheetConvertOptions--}
```
public SpreadsheetConvertOptions()
```


Menginisialisasi instance baru dari kelas [SpreadsheetConvertOptions](../../com.groupdocs.conversion.options.convert/spreadsheetconvertoptions).


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


**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


Menentukan tingkat zoom dalam persentase. Defaultnya adalah 100.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getSeparator() {#getSeparator--}
```
public char getSeparator()
```


Menentukan pemisah yang akan digunakan saat mengonversi ke format terdelimit.


**Returns:**
char
### setSeparator(char separator) {#setSeparator-char-}
```
public void setSeparator(char separator)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pemisah | char |  |

### setFormat(FileType value) {#setFormat-com.groupdocs.conversion.filetypes.FileType-}
```
public void setFormat(FileType value)
```


Tipe file yang diinginkan untuk dokumen input yang akan dikonversi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |

