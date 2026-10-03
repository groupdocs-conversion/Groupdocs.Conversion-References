---
title: "CsvLoadOptions"
second_title: "GroupDocs.Conversion för Java API-referens"
description: "Alternativ för inläsning av Csv-dokument."
type: docs
weight: 13
url: /sv/java/com.groupdocs.conversion.options.load/csvloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions), [com.groupdocs.conversion.options.load.SpreadsheetLoadOptions](../../com.groupdocs.conversion.options.load/spreadsheetloadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class CsvLoadOptions extends SpreadsheetLoadOptions implements Serializable
```

Alternativ för inläsning av Csv-dokument.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [CsvLoadOptions()](#CsvLoadOptions--) | Initierar en ny instans av klassen [CsvLoadOptions](../../com.groupdocs.conversion.options.load/csvloadoptions). |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getSeparator()](#getSeparator--) | Avgränsare för en CSV-fil. |
|
|  | [setSeparator(char value)](#setSeparator-char-) | Avgränsare för en CSV-fil. |
|
|  | [isMultiEncoded()](#isMultiEncoded--) | True betyder att filen innehåller flera kodningar. |
|
|  | [setMultiEncoded(boolean value)](#setMultiEncoded-boolean-) | True betyder att filen innehåller flera kodningar. |
|
|  | [hasFormula()](#hasFormula--) | Indikerar om text är en formel om den börjar med "=". |
|
|  | [setFormula(boolean value)](#setFormula-boolean-) | Indikerar om text är en formel om den börjar med "=". |
|
|  | [getConvertNumericData()](#getConvertNumericData--) | Indikerar om strängen i filen konverteras till numerisk. |
|
|  | [setConvertNumericData(boolean value)](#setConvertNumericData-boolean-) | Indikerar om strängen i filen konverteras till numerisk. |
|
|  | [getConvertDateTimeData()](#getConvertDateTimeData--) | Indikerar om strängen i filen konverteras till datum. |
|
|  | [setConvertDateTimeData(boolean value)](#setConvertDateTimeData-boolean-) | Indikerar om strängen i filen konverteras till datum. |
|
|  | [getEncoding()](#getEncoding--) | Kodning. |
|
| [getEncodingInternal()](#getEncodingInternal--) |  |
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Kodning. |
|
| [setEncodingInternal(System.Text.Encoding value)](#setEncodingInternal-com.aspose.ms.System.Text.Encoding-) |  |
### CsvLoadOptions() {#CsvLoadOptions--}
```
public CsvLoadOptions()
```


Initierar en ny instans av klassen [CsvLoadOptions](../../com.groupdocs.conversion.options.load/csvloadoptions).


### getSeparator() {#getSeparator--}
```
public final char getSeparator()
```


Avgränsare för en CSV-fil.


**Returns:**
char
### setSeparator(char value) {#setSeparator-char-}
```
public final void setSeparator(char value)
```


Avgränsare för en CSV-fil.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | char |  |

### isMultiEncoded() {#isMultiEncoded--}
```
public final boolean isMultiEncoded()
```


True betyder att filen innehåller flera kodningar.


**Returns:**
boolean
### setMultiEncoded(boolean value) {#setMultiEncoded-boolean-}
```
public final void setMultiEncoded(boolean value)
```


True betyder att filen innehåller flera kodningar.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### hasFormula() {#hasFormula--}
```
public final boolean hasFormula()
```


Indikerar om text är en formel om den börjar med "=".


**Returns:**
boolean
### setFormula(boolean value) {#setFormula-boolean-}
```
public final void setFormula(boolean value)
```


Indikerar om text är en formel om den börjar med "=".


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getConvertNumericData() {#getConvertNumericData--}
```
public final boolean getConvertNumericData()
```


Indikerar om strängen i filen konverteras till numerisk. Standard är True.


**Returns:**
boolean
### setConvertNumericData(boolean value) {#setConvertNumericData-boolean-}
```
public final void setConvertNumericData(boolean value)
```


Indikerar om strängen i filen konverteras till numerisk. Standard är True.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getConvertDateTimeData() {#getConvertDateTimeData--}
```
public final boolean getConvertDateTimeData()
```


Indikerar om strängen i filen konverteras till datum. Standard är True.


**Returns:**
boolean
### setConvertDateTimeData(boolean value) {#setConvertDateTimeData-boolean-}
```
public final void setConvertDateTimeData(boolean value)
```


Indikerar om strängen i filen konverteras till datum. Standard är True.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Kodning. Standard är Encoding.Default.


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


Kodning. Standard är Encoding.Default.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.nio.charset.Charset |  |

### setEncodingInternal(System.Text.Encoding value) {#setEncodingInternal-com.aspose.ms.System.Text.Encoding-}
```
public void setEncodingInternal(System.Text.Encoding value)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | com.aspose.ms.System.Text.Encoding |  |

