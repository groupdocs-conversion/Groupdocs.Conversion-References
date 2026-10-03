---
title: "CsvLoadOptions"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Opzioni per il caricamento dei documenti Csv."
type: docs
weight: 13
url: /it/java/com.groupdocs.conversion.options.load/csvloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions), [com.groupdocs.conversion.options.load.SpreadsheetLoadOptions](../../com.groupdocs.conversion.options.load/spreadsheetloadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class CsvLoadOptions extends SpreadsheetLoadOptions implements Serializable
```

Opzioni per il caricamento dei documenti Csv.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [CsvLoadOptions()](#CsvLoadOptions--) | Inizializza una nuova istanza della classe [CsvLoadOptions](../../com.groupdocs.conversion.options.load/csvloadoptions). |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getSeparator()](#getSeparator--) | Delimitatore di un file Csv. |
|
|  | [setSeparator(char value)](#setSeparator-char-) | Delimitatore di un file Csv. |
|
|  | [isMultiEncoded()](#isMultiEncoded--) | True indica che il file contiene diverse codifiche. |
|
|  | [setMultiEncoded(boolean value)](#setMultiEncoded-boolean-) | True indica che il file contiene diverse codifiche. |
|
|  | [hasFormula()](#hasFormula--) | Indica se il testo è una formula se inizia con "=", |
|
|  | [setFormula(boolean value)](#setFormula-boolean-) | Indica se il testo è una formula se inizia con "=", |
|
|  | [getConvertNumericData()](#getConvertNumericData--) | Indica se la stringa nel file viene convertita in numerico. |
|
|  | [setConvertNumericData(boolean value)](#setConvertNumericData-boolean-) | Indica se la stringa nel file viene convertita in numerico. |
|
|  | [getConvertDateTimeData()](#getConvertDateTimeData--) | Indica se la stringa nel file viene convertita in data. |
|
|  | [setConvertDateTimeData(boolean value)](#setConvertDateTimeData-boolean-) | Indica se la stringa nel file viene convertita in data. |
|
|  | [getEncoding()](#getEncoding--) | Codifica. |
|
| [getEncodingInternal()](#getEncodingInternal--) |  |
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Codifica. |
|
| [setEncodingInternal(System.Text.Encoding value)](#setEncodingInternal-com.aspose.ms.System.Text.Encoding-) |  |
### CsvLoadOptions() {#CsvLoadOptions--}
```
public CsvLoadOptions()
```


Inizializza una nuova istanza della classe [CsvLoadOptions](../../com.groupdocs.conversion.options.load/csvloadoptions).


### getSeparator() {#getSeparator--}
```
public final char getSeparator()
```


Delimitatore di un file Csv.


**Returns:**
char
### setSeparator(char value) {#setSeparator-char-}
```
public final void setSeparator(char value)
```


Delimitatore di un file Csv.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | char |  |

### isMultiEncoded() {#isMultiEncoded--}
```
public final boolean isMultiEncoded()
```


True indica che il file contiene diverse codifiche.


**Returns:**
booleano
### setMultiEncoded(boolean value) {#setMultiEncoded-boolean-}
```
public final void setMultiEncoded(boolean value)
```


True indica che il file contiene diverse codifiche.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | booleano |  |

### hasFormula() {#hasFormula--}
```
public final boolean hasFormula()
```


Indica se il testo è una formula se inizia con "=",


**Returns:**
booleano
### setFormula(boolean value) {#setFormula-boolean-}
```
public final void setFormula(boolean value)
```


Indica se il testo è una formula se inizia con "=",


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | booleano |  |

### getConvertNumericData() {#getConvertNumericData--}
```
public final boolean getConvertNumericData()
```


Indica se la stringa nel file viene convertita in numerico. Il valore predefinito è True.


**Returns:**
booleano
### setConvertNumericData(boolean value) {#setConvertNumericData-boolean-}
```
public final void setConvertNumericData(boolean value)
```


Indica se la stringa nel file viene convertita in numerico. Il valore predefinito è True.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | booleano |  |

### getConvertDateTimeData() {#getConvertDateTimeData--}
```
public final boolean getConvertDateTimeData()
```


Indica se la stringa nel file viene convertita in data. Il valore predefinito è True.


**Returns:**
booleano
### setConvertDateTimeData(boolean value) {#setConvertDateTimeData-boolean-}
```
public final void setConvertDateTimeData(boolean value)
```


Indica se la stringa nel file viene convertita in data. Il valore predefinito è True.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | booleano |  |

### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Codifica. Il valore predefinito è Encoding.Default.


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


Codifica. Il valore predefinito è Encoding.Default.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.nio.charset.Charset |  |

### setEncodingInternal(System.Text.Encoding value) {#setEncodingInternal-com.aspose.ms.System.Text.Encoding-}
```
public void setEncodingInternal(System.Text.Encoding value)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | com.aspose.ms.System.Text.Encoding |  |

