---
title: "CsvLoadOptions"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Opsi untuk memuat dokumen Csv."
type: docs
weight: 13
url: /id/java/com.groupdocs.conversion.options.load/csvloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions), [com.groupdocs.conversion.options.load.SpreadsheetLoadOptions](../../com.groupdocs.conversion.options.load/spreadsheetloadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class CsvLoadOptions extends SpreadsheetLoadOptions implements Serializable
```

Opsi untuk memuat dokumen Csv.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [CsvLoadOptions()](#CsvLoadOptions--) | Menginisialisasi instance baru dari kelas [CsvLoadOptions](../../com.groupdocs.conversion.options.load/csvloadoptions). |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getSeparator()](#getSeparator--) | Pembatas file Csv. |
|
|  | [setSeparator(char value)](#setSeparator-char-) | Pembatas file Csv. |
|
|  | [isMultiEncoded()](#isMultiEncoded--) | True berarti file berisi beberapa enkoding. |
|
|  | [setMultiEncoded(boolean value)](#setMultiEncoded-boolean-) | True berarti file berisi beberapa enkoding. |
|
|  | [hasFormula()](#hasFormula--) | Menunjukkan apakah teks adalah formula jika dimulai dengan "=". |
|
|  | [setFormula(boolean value)](#setFormula-boolean-) | Menunjukkan apakah teks adalah formula jika dimulai dengan "=". |
|
|  | [getConvertNumericData()](#getConvertNumericData--) | Menunjukkan apakah string dalam file dikonversi menjadi numerik. |
|
|  | [setConvertNumericData(boolean value)](#setConvertNumericData-boolean-) | Menunjukkan apakah string dalam file dikonversi menjadi numerik. |
|
|  | [getConvertDateTimeData()](#getConvertDateTimeData--) | Menunjukkan apakah string dalam file dikonversi menjadi tanggal. |
|
|  | [setConvertDateTimeData(boolean value)](#setConvertDateTimeData-boolean-) | Menunjukkan apakah string dalam file dikonversi menjadi tanggal. |
|
|  | [getEncoding()](#getEncoding--) | Pengkodean. |
|
| [getEncodingInternal()](#getEncodingInternal--) |  |
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Pengkodean. |
|
| [setEncodingInternal(System.Text.Encoding value)](#setEncodingInternal-com.aspose.ms.System.Text.Encoding-) |  |
### CsvLoadOptions() {#CsvLoadOptions--}
```
public CsvLoadOptions()
```


Menginisialisasi instance baru dari kelas [CsvLoadOptions](../../com.groupdocs.conversion.options.load/csvloadoptions).


### getSeparator() {#getSeparator--}
```
public final char getSeparator()
```


Pembatas file Csv.


**Returns:**
char
### setSeparator(char value) {#setSeparator-char-}
```
public final void setSeparator(char value)
```


Pembatas file Csv.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | char |  |

### isMultiEncoded() {#isMultiEncoded--}
```
public final boolean isMultiEncoded()
```


True berarti file berisi beberapa enkoding.


**Returns:**
boolean
### setMultiEncoded(boolean value) {#setMultiEncoded-boolean-}
```
public final void setMultiEncoded(boolean value)
```


True berarti file berisi beberapa enkoding.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### hasFormula() {#hasFormula--}
```
public final boolean hasFormula()
```


Menunjukkan apakah teks adalah formula jika dimulai dengan "=".


**Returns:**
boolean
### setFormula(boolean value) {#setFormula-boolean-}
```
public final void setFormula(boolean value)
```


Menunjukkan apakah teks adalah formula jika dimulai dengan "=".


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getConvertNumericData() {#getConvertNumericData--}
```
public final boolean getConvertNumericData()
```


Menunjukkan apakah string dalam file dikonversi menjadi numerik. Default adalah True.


**Returns:**
boolean
### setConvertNumericData(boolean value) {#setConvertNumericData-boolean-}
```
public final void setConvertNumericData(boolean value)
```


Menunjukkan apakah string dalam file dikonversi menjadi numerik. Default adalah True.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getConvertDateTimeData() {#getConvertDateTimeData--}
```
public final boolean getConvertDateTimeData()
```


Menunjukkan apakah string dalam file dikonversi menjadi tanggal. Default adalah True.


**Returns:**
boolean
### setConvertDateTimeData(boolean value) {#setConvertDateTimeData-boolean-}
```
public final void setConvertDateTimeData(boolean value)
```


Menunjukkan apakah string dalam file dikonversi menjadi tanggal. Default adalah True.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Pengkodean. Default adalah Encoding.Default.


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


Pengkodean. Default adalah Encoding.Default.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.nio.charset.Charset |  |

### setEncodingInternal(System.Text.Encoding value) {#setEncodingInternal-com.aspose.ms.System.Text.Encoding-}
```
public void setEncodingInternal(System.Text.Encoding value)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | com.aspose.ms.System.Text.Encoding |  |

