---
title: "CsvLoadOptions"
second_title: "Java için GroupDocs.Conversion API Referansı"
description: "Csv belgelerini yükleme seçenekleri."
type: docs
weight: 13
url: /tr/java/com.groupdocs.conversion.options.load/csvloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions), [com.groupdocs.conversion.options.load.SpreadsheetLoadOptions](../../com.groupdocs.conversion.options.load/spreadsheetloadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class CsvLoadOptions extends SpreadsheetLoadOptions implements Serializable
```

Csv belgelerini yükleme seçenekleri.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [CsvLoadOptions()](#CsvLoadOptions--) | Yeni bir [CsvLoadOptions](../../com.groupdocs.conversion.options.load/csvloadoptions) sınıfının örneğini başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getSeparator()](#getSeparator--) | Csv dosyasının ayırıcı karakteri. |
|
|  | [setSeparator(char value)](#setSeparator-char-) | Csv dosyasının ayırıcı karakteri. |
|
|  | [isMultiEncoded()](#isMultiEncoded--) | True, dosyanın birden fazla kodlama içerdiği anlamına gelir. |
|
|  | [setMultiEncoded(boolean value)](#setMultiEncoded-boolean-) | True, dosyanın birden fazla kodlama içerdiği anlamına gelir. |
|
|  | [hasFormula()](#hasFormula--) | Metnin "=" ile başlaması durumunda formül olup olmadığını gösterir. |
|
|  | [setFormula(boolean value)](#setFormula-boolean-) | Metnin "=" ile başlaması durumunda formül olup olmadığını gösterir. |
|
|  | [getConvertNumericData()](#getConvertNumericData--) | Dosyadaki dizgenin sayısala dönüştürülüp dönüştürülmediğini gösterir. |
|
|  | [setConvertNumericData(boolean value)](#setConvertNumericData-boolean-) | Dosyadaki dizgenin sayısala dönüştürülüp dönüştürülmediğini gösterir. |
|
|  | [getConvertDateTimeData()](#getConvertDateTimeData--) | Dosyadaki dizgenin tarihe dönüştürülüp dönüştürülmediğini gösterir. |
|
|  | [setConvertDateTimeData(boolean value)](#setConvertDateTimeData-boolean-) | Dosyadaki dizgenin tarihe dönüştürülüp dönüştürülmediğini gösterir. |
|
|  | [getEncoding()](#getEncoding--) | Kodlama. |
|
| [getEncodingInternal()](#getEncodingInternal--) |  |
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Kodlama. |
|
| [setEncodingInternal(System.Text.Encoding value)](#setEncodingInternal-com.aspose.ms.System.Text.Encoding-) |  |
### CsvLoadOptions() {#CsvLoadOptions--}
```
public CsvLoadOptions()
```


Yeni bir [CsvLoadOptions](../../com.groupdocs.conversion.options.load/csvloadoptions) sınıfının örneğini başlatır.


### getSeparator() {#getSeparator--}
```
public final char getSeparator()
```


Csv dosyasının ayırıcı karakteri.


**Returns:**
char
### setSeparator(char value) {#setSeparator-char-}
```
public final void setSeparator(char value)
```


Csv dosyasının ayırıcı karakteri.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | char |  |

### isMultiEncoded() {#isMultiEncoded--}
```
public final boolean isMultiEncoded()
```


True, dosyanın birden fazla kodlama içerdiği anlamına gelir.


**Returns:**
boolean
### setMultiEncoded(boolean value) {#setMultiEncoded-boolean-}
```
public final void setMultiEncoded(boolean value)
```


True, dosyanın birden fazla kodlama içerdiği anlamına gelir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### hasFormula() {#hasFormula--}
```
public final boolean hasFormula()
```


Metnin "=" ile başlaması durumunda formül olup olmadığını gösterir.


**Returns:**
boolean
### setFormula(boolean value) {#setFormula-boolean-}
```
public final void setFormula(boolean value)
```


Metnin "=" ile başlaması durumunda formül olup olmadığını gösterir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getConvertNumericData() {#getConvertNumericData--}
```
public final boolean getConvertNumericData()
```


Dosyadaki dizeyin sayısala dönüştürülüp dönüştürülmediğini gösterir. Varsayılan True'dur.


**Returns:**
boolean
### setConvertNumericData(boolean value) {#setConvertNumericData-boolean-}
```
public final void setConvertNumericData(boolean value)
```


Dosyadaki dizeyin sayısala dönüştürülüp dönüştürülmediğini gösterir. Varsayılan True'dur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getConvertDateTimeData() {#getConvertDateTimeData--}
```
public final boolean getConvertDateTimeData()
```


Dosyadaki dizeyin tarihe dönüştürülüp dönüştürülmediğini gösterir. Varsayılan True'dur.


**Returns:**
boolean
### setConvertDateTimeData(boolean value) {#setConvertDateTimeData-boolean-}
```
public final void setConvertDateTimeData(boolean value)
```


Dosyadaki dizeyin tarihe dönüştürülüp dönüştürülmediğini gösterir. Varsayılan True'dur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Kodlama. Varsayılan Encoding.Default.


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


Kodlama. Varsayılan Encoding.Default.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.nio.charset.Charset |  |

### setEncodingInternal(System.Text.Encoding value) {#setEncodingInternal-com.aspose.ms.System.Text.Encoding-}
```
public void setEncodingInternal(System.Text.Encoding value)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | com.aspose.ms.System.Text.Encoding |  |

