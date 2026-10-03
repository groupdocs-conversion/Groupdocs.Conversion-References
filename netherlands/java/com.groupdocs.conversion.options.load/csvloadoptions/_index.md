---
title: "CsvLoadOptions"
second_title: "GroupDocs.Conversion voor Java API-referentie"
description: "Opties voor het laden van Csv-documenten."
type: docs
weight: 13
url: /nl/java/com.groupdocs.conversion.options.load/csvloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions), [com.groupdocs.conversion.options.load.SpreadsheetLoadOptions](../../com.groupdocs.conversion.options.load/spreadsheetloadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class CsvLoadOptions extends SpreadsheetLoadOptions implements Serializable
```

Opties voor het laden van Csv-documenten.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [CsvLoadOptions()](#CsvLoadOptions--) | Initialiseert een nieuw exemplaar van de klasse [CsvLoadOptions](../../com.groupdocs.conversion.options.load/csvloadoptions). |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getSeparator()](#getSeparator--) | Scheidingsteken van een Csv-bestand. |
|
|  | [setSeparator(char value)](#setSeparator-char-) | Scheidingsteken van een Csv-bestand. |
|
|  | [isMultiEncoded()](#isMultiEncoded--) | True betekent dat het bestand meerdere coderingen bevat. |
|
|  | [setMultiEncoded(boolean value)](#setMultiEncoded-boolean-) | True betekent dat het bestand meerdere coderingen bevat. |
|
|  | [hasFormula()](#hasFormula--) | Geeft aan of tekst een formule is als deze begint met "=". |
|
|  | [setFormula(boolean value)](#setFormula-boolean-) | Geeft aan of tekst een formule is als deze begint met "=". |
|
|  | [getConvertNumericData()](#getConvertNumericData--) | Geeft aan of de tekenreeks in het bestand wordt geconverteerd naar numeriek. |
|
|  | [setConvertNumericData(boolean value)](#setConvertNumericData-boolean-) | Geeft aan of de tekenreeks in het bestand wordt geconverteerd naar numeriek. |
|
|  | [getConvertDateTimeData()](#getConvertDateTimeData--) | Geeft aan of de tekenreeks in het bestand wordt geconverteerd naar een datum. |
|
|  | [setConvertDateTimeData(boolean value)](#setConvertDateTimeData-boolean-) | Geeft aan of de tekenreeks in het bestand wordt geconverteerd naar een datum. |
|
|  | [getEncoding()](#getEncoding--) | Encoding. |
|
| [getEncodingInternal()](#getEncodingInternal--) |  |
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Encoding. |
|
| [setEncodingInternal(System.Text.Encoding value)](#setEncodingInternal-com.aspose.ms.System.Text.Encoding-) |  |
### CsvLoadOptions() {#CsvLoadOptions--}
```
public CsvLoadOptions()
```


Initialiseert een nieuw exemplaar van de klasse [CsvLoadOptions](../../com.groupdocs.conversion.options.load/csvloadoptions).


### getSeparator() {#getSeparator--}
```
public final char getSeparator()
```


Scheidingsteken van een Csv-bestand.


**Returns:**
char
### setSeparator(char value) {#setSeparator-char-}
```
public final void setSeparator(char value)
```


Scheidingsteken van een Csv-bestand.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | char |  |

### isMultiEncoded() {#isMultiEncoded--}
```
public final boolean isMultiEncoded()
```


True betekent dat het bestand meerdere coderingen bevat.


**Returns:**
boolean
### setMultiEncoded(boolean value) {#setMultiEncoded-boolean-}
```
public final void setMultiEncoded(boolean value)
```


True betekent dat het bestand meerdere coderingen bevat.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### hasFormula() {#hasFormula--}
```
public final boolean hasFormula()
```


Geeft aan of tekst een formule is als deze begint met "=".


**Returns:**
boolean
### setFormula(boolean value) {#setFormula-boolean-}
```
public final void setFormula(boolean value)
```


Geeft aan of tekst een formule is als deze begint met "=".


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getConvertNumericData() {#getConvertNumericData--}
```
public final boolean getConvertNumericData()
```


Geeft aan of de tekenreeks in het bestand wordt geconverteerd naar numeriek. Standaard is True.


**Returns:**
boolean
### setConvertNumericData(boolean value) {#setConvertNumericData-boolean-}
```
public final void setConvertNumericData(boolean value)
```


Geeft aan of de tekenreeks in het bestand wordt geconverteerd naar numeriek. Standaard is True.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getConvertDateTimeData() {#getConvertDateTimeData--}
```
public final boolean getConvertDateTimeData()
```


Geeft aan of de tekenreeks in het bestand wordt geconverteerd naar datum. Standaard is True.


**Returns:**
boolean
### setConvertDateTimeData(boolean value) {#setConvertDateTimeData-boolean-}
```
public final void setConvertDateTimeData(boolean value)
```


Geeft aan of de tekenreeks in het bestand wordt geconverteerd naar datum. Standaard is True.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Encoding. Standaard is Encoding.Default.


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


Encoding. Standaard is Encoding.Default.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.nio.charset.Charset |  |

### setEncodingInternal(System.Text.Encoding value) {#setEncodingInternal-com.aspose.ms.System.Text.Encoding-}
```
public void setEncodingInternal(System.Text.Encoding value)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | com.aspose.ms.System.Text.Encoding |  |

