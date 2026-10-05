---
title: "CsvLoadOptions"
second_title: "GroupDocs.Conversion för Node.js via Java API-referens"
description: "Alternativ för inläsning av Csv-dokument."
type: docs
weight: 14
url: /sv/nodejs-java/com.groupdocs.conversion.options.load/csvloadoptions/
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
| [CsvLoadOptions()](#CsvLoadOptions--) | Initierar en ny instans av [CsvLoadOptions](../../com.groupdocs.conversion.options.load/csvloadoptions) klass. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getSeparator()](#getSeparator--) | Avgränsare för en Csv-fil. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | Avgränsare för en Csv-fil. |
| [setSeparator(char value)](#setSeparator-char-) | Avgränsare för en Csv-fil. |
| [isMultiEncoded()](#isMultiEncoded--) | True betyder att filen innehåller flera kodningar. |
| [setMultiEncoded(boolean value)](#setMultiEncoded-boolean-) | True betyder att filen innehåller flera kodningar. |
| [hasFormula()](#hasFormula--) | Indikerar om text är en formel om den börjar med "=". |
| [setFormula(boolean value)](#setFormula-boolean-) | Indikerar om text är en formel om den börjar med "=". |
| [getConvertNumericData()](#getConvertNumericData--) | Indikerar om strängen i filen konverteras till numerisk. |
| [setConvertNumericData(boolean value)](#setConvertNumericData-boolean-) | Indikerar om strängen i filen konverteras till numerisk. |
| [getConvertDateTimeData()](#getConvertDateTimeData--) | Indikerar om strängen i filen konverteras till datum. |
| [setConvertDateTimeData(boolean value)](#setConvertDateTimeData-boolean-) | Indikerar om strängen i filen konverteras till datum. |
| [getEncoding()](#getEncoding--) | Kodning. |
| [getEncodingInternal()](#getEncodingInternal--) |  |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Kodning. |
| [setEncoding(String charsetName)](#setEncoding-java.lang.String-) | Hämtar eller anger kodningen som ska användas vid inläsning av Txt-dokument. |
| [setEncodingInternal(System.Text.Encoding value)](#setEncodingInternal-com.aspose.ms.System.Text.Encoding-) |  |
### CsvLoadOptions() {#CsvLoadOptions--}
```
public CsvLoadOptions()
```


Initierar en ny instans av [CsvLoadOptions](../../com.groupdocs.conversion.options.load/csvloadoptions) klass.

### getSeparator() {#getSeparator--}
```
public final char getSeparator()
```


Avgränsare för en Csv-fil.

**Returns:**
char
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```


Avgränsare för en Csv-fil.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### setSeparator(char value) {#setSeparator-char-}
```
public final void setSeparator(char value)
```


Avgränsare för en Csv-fil.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | char |  |

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
| value | boolean |  |

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
| value | boolean |  |

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
| value | boolean |  |

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
| value | boolean |  |

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
| value | java.nio.charset.Charset |  |

### setEncoding(String charsetName) {#setEncoding-java.lang.String-}
```
public final void setEncoding(String charsetName)
```


Hämtar eller anger kodningen som ska användas när Txt-dokument laddas. Kan vara null. Standard är null.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| charsetName | java.lang.String |  |

### setEncodingInternal(System.Text.Encoding value) {#setEncodingInternal-com.aspose.ms.System.Text.Encoding-}
```
public void setEncodingInternal(System.Text.Encoding value)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | com.aspose.ms.System.Text.Encoding |  |

