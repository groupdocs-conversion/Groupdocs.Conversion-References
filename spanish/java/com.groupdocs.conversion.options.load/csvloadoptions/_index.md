---
title: "CsvLoadOptions"
second_title: "Referencia de API de GroupDocs.Conversion for Java"
description: "Opciones para cargar documentos CSV."
type: docs
weight: 13
url: /es/java/com.groupdocs.conversion.options.load/csvloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions), [com.groupdocs.conversion.options.load.SpreadsheetLoadOptions](../../com.groupdocs.conversion.options.load/spreadsheetloadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class CsvLoadOptions extends SpreadsheetLoadOptions implements Serializable
```

Opciones para cargar documentos CSV.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [CsvLoadOptions()](#CsvLoadOptions--) | Inicializa una nueva instancia de la clase [CsvLoadOptions](../../com.groupdocs.conversion.options.load/csvloadoptions). |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getSeparator()](#getSeparator--) | Delimitador de un archivo Csv. |
|
|  | [setSeparator(char value)](#setSeparator-char-) | Delimitador de un archivo Csv. |
|
|  | [isMultiEncoded()](#isMultiEncoded--) | True indica que el archivo contiene varias codificaciones. |
|
|  | [setMultiEncoded(boolean value)](#setMultiEncoded-boolean-) | True indica que el archivo contiene varias codificaciones. |
|
|  | [hasFormula()](#hasFormula--) | Indica si el texto es una fórmula si comienza con "=". |
|
|  | [setFormula(boolean value)](#setFormula-boolean-) | Indica si el texto es una fórmula si comienza con "=". |
|
|  | [getConvertNumericData()](#getConvertNumericData--) | Indica si la cadena en el archivo se convierte a numérico. |
|
|  | [setConvertNumericData(boolean value)](#setConvertNumericData-boolean-) | Indica si la cadena en el archivo se convierte a numérico. |
|
|  | [getConvertDateTimeData()](#getConvertDateTimeData--) | Indica si la cadena en el archivo se convierte a fecha. |
|
|  | [setConvertDateTimeData(boolean value)](#setConvertDateTimeData-boolean-) | Indica si la cadena en el archivo se convierte a fecha. |
|
|  | [getEncoding()](#getEncoding--) | Codificación. |
|
| [getEncodingInternal()](#getEncodingInternal--) |  |
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Codificación. |
|
| [setEncodingInternal(System.Text.Encoding value)](#setEncodingInternal-com.aspose.ms.System.Text.Encoding-) |  |
### CsvLoadOptions() {#CsvLoadOptions--}
```
public CsvLoadOptions()
```


Inicializa una nueva instancia de la clase [CsvLoadOptions](../../com.groupdocs.conversion.options.load/csvloadoptions).


### getSeparator() {#getSeparator--}
```
public final char getSeparator()
```


Delimitador de un archivo Csv.


**Returns:**
char
### setSeparator(char value) {#setSeparator-char-}
```
public final void setSeparator(char value)
```


Delimitador de un archivo Csv.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | char |  |

### isMultiEncoded() {#isMultiEncoded--}
```
public final boolean isMultiEncoded()
```


True indica que el archivo contiene varias codificaciones.


**Returns:**
booleano
### setMultiEncoded(boolean value) {#setMultiEncoded-boolean-}
```
public final void setMultiEncoded(boolean value)
```


True indica que el archivo contiene varias codificaciones.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | booleano |  |

### hasFormula() {#hasFormula--}
```
public final boolean hasFormula()
```


Indica si el texto es una fórmula si comienza con "=".


**Returns:**
booleano
### setFormula(boolean value) {#setFormula-boolean-}
```
public final void setFormula(boolean value)
```


Indica si el texto es una fórmula si comienza con "=".


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | booleano |  |

### getConvertNumericData() {#getConvertNumericData--}
```
public final boolean getConvertNumericData()
```


Indica si la cadena en el archivo se convierte a numérico. El valor predeterminado es True.


**Returns:**
booleano
### setConvertNumericData(boolean value) {#setConvertNumericData-boolean-}
```
public final void setConvertNumericData(boolean value)
```


Indica si la cadena en el archivo se convierte a numérico. El valor predeterminado es True.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | booleano |  |

### getConvertDateTimeData() {#getConvertDateTimeData--}
```
public final boolean getConvertDateTimeData()
```


Indica si la cadena en el archivo se convierte a fecha. El valor predeterminado es True.


**Returns:**
booleano
### setConvertDateTimeData(boolean value) {#setConvertDateTimeData-boolean-}
```
public final void setConvertDateTimeData(boolean value)
```


Indica si la cadena en el archivo se convierte a fecha. El valor predeterminado es True.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | booleano |  |

### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Codificación. El valor predeterminado es Encoding.Default.


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


Codificación. El valor predeterminado es Encoding.Default.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.nio.charset.Charset |  |

### setEncodingInternal(System.Text.Encoding value) {#setEncodingInternal-com.aspose.ms.System.Text.Encoding-}
```
public void setEncodingInternal(System.Text.Encoding value)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | com.aspose.ms.System.Text.Encoding |  |

