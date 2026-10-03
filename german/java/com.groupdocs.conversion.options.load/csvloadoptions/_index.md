---
title: "CsvLoadOptions"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Optionen zum Laden von CSV-Dokumenten."
type: docs
weight: 13
url: /de/java/com.groupdocs.conversion.options.load/csvloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions), [com.groupdocs.conversion.options.load.SpreadsheetLoadOptions](../../com.groupdocs.conversion.options.load/spreadsheetloadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class CsvLoadOptions extends SpreadsheetLoadOptions implements Serializable
```

Optionen zum Laden von CSV-Dokumenten.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [CsvLoadOptions()](#CsvLoadOptions--) | Initialisiert eine neue Instanz der Klasse [CsvLoadOptions](../../com.groupdocs.conversion.options.load/csvloadoptions). |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getSeparator()](#getSeparator--) | Trennzeichen einer Csv-Datei. |
|
|  | [setSeparator(char value)](#setSeparator-char-) | Trennzeichen einer Csv-Datei. |
|
|  | [isMultiEncoded()](#isMultiEncoded--) | True bedeutet, dass die Datei mehrere Codierungen enthält. |
|
|  | [setMultiEncoded(boolean value)](#setMultiEncoded-boolean-) | True bedeutet, dass die Datei mehrere Codierungen enthält. |
|
|  | [hasFormula()](#hasFormula--) | Gibt an, ob Text eine Formel ist, wenn er mit "=" beginnt. |
|
|  | [setFormula(boolean value)](#setFormula-boolean-) | Gibt an, ob Text eine Formel ist, wenn er mit "=" beginnt. |
|
|  | [getConvertNumericData()](#getConvertNumericData--) | Gibt an, ob die Zeichenkette in der Datei in numerisch konvertiert wird. |
|
|  | [setConvertNumericData(boolean value)](#setConvertNumericData-boolean-) | Gibt an, ob die Zeichenkette in der Datei in numerisch konvertiert wird. |
|
|  | [getConvertDateTimeData()](#getConvertDateTimeData--) | Gibt an, ob die Zeichenkette in der Datei in ein Datum konvertiert wird. |
|
|  | [setConvertDateTimeData(boolean value)](#setConvertDateTimeData-boolean-) | Gibt an, ob die Zeichenkette in der Datei in ein Datum konvertiert wird. |
|
|  | [getEncoding()](#getEncoding--) | Kodierung. |
|
| [getEncodingInternal()](#getEncodingInternal--) |  |
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Kodierung. |
|
| [setEncodingInternal(System.Text.Encoding value)](#setEncodingInternal-com.aspose.ms.System.Text.Encoding-) |  |
### CsvLoadOptions() {#CsvLoadOptions--}
```
public CsvLoadOptions()
```


Initialisiert eine neue Instanz der Klasse [CsvLoadOptions](../../com.groupdocs.conversion.options.load/csvloadoptions).


### getSeparator() {#getSeparator--}
```
public final char getSeparator()
```


Trennzeichen einer Csv-Datei.


**Returns:**
char
### setSeparator(char value) {#setSeparator-char-}
```
public final void setSeparator(char value)
```


Trennzeichen einer Csv-Datei.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | char |  |

### isMultiEncoded() {#isMultiEncoded--}
```
public final boolean isMultiEncoded()
```


True bedeutet, dass die Datei mehrere Codierungen enthält.


**Returns:**
boolean
### setMultiEncoded(boolean value) {#setMultiEncoded-boolean-}
```
public final void setMultiEncoded(boolean value)
```


True bedeutet, dass die Datei mehrere Codierungen enthält.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### hasFormula() {#hasFormula--}
```
public final boolean hasFormula()
```


Gibt an, ob Text eine Formel ist, wenn er mit "=" beginnt.


**Returns:**
boolean
### setFormula(boolean value) {#setFormula-boolean-}
```
public final void setFormula(boolean value)
```


Gibt an, ob Text eine Formel ist, wenn er mit "=" beginnt.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getConvertNumericData() {#getConvertNumericData--}
```
public final boolean getConvertNumericData()
```


Gibt an, ob die Zeichenkette in der Datei in numerisch konvertiert wird. Standard ist True.


**Returns:**
boolean
### setConvertNumericData(boolean value) {#setConvertNumericData-boolean-}
```
public final void setConvertNumericData(boolean value)
```


Gibt an, ob die Zeichenkette in der Datei in numerisch konvertiert wird. Standard ist True.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getConvertDateTimeData() {#getConvertDateTimeData--}
```
public final boolean getConvertDateTimeData()
```


Gibt an, ob die Zeichenkette in der Datei in ein Datum konvertiert wird. Standard ist True.


**Returns:**
boolean
### setConvertDateTimeData(boolean value) {#setConvertDateTimeData-boolean-}
```
public final void setConvertDateTimeData(boolean value)
```


Gibt an, ob die Zeichenkette in der Datei in ein Datum konvertiert wird. Standard ist True.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Kodierung. Standard ist Encoding.Default.


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


Kodierung. Standard ist Encoding.Default.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.nio.charset.Charset |  |

### setEncodingInternal(System.Text.Encoding value) {#setEncodingInternal-com.aspose.ms.System.Text.Encoding-}
```
public void setEncodingInternal(System.Text.Encoding value)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | com.aspose.ms.System.Text.Encoding |  |

