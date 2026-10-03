---
title: "CsvLoadOptions"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Options de chargement des documents Csv."
type: docs
weight: 13
url: /fr/java/com.groupdocs.conversion.options.load/csvloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions), [com.groupdocs.conversion.options.load.SpreadsheetLoadOptions](../../com.groupdocs.conversion.options.load/spreadsheetloadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class CsvLoadOptions extends SpreadsheetLoadOptions implements Serializable
```

Options de chargement des documents Csv.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [CsvLoadOptions()](#CsvLoadOptions--) | Initialise une nouvelle instance de la classe [CsvLoadOptions](../../com.groupdocs.conversion.options.load/csvloadoptions). |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getSeparator()](#getSeparator--) | Délimiteur d'un fichier Csv. |
|
|  | [setSeparator(char value)](#setSeparator-char-) | Délimiteur d'un fichier Csv. |
|
|  | [isMultiEncoded()](#isMultiEncoded--) | Vrai signifie que le fichier contient plusieurs encodages. |
|
|  | [setMultiEncoded(boolean value)](#setMultiEncoded-boolean-) | Vrai signifie que le fichier contient plusieurs encodages. |
|
|  | [hasFormula()](#hasFormula--) | Indique si le texte est une formule s'il commence par "=","Indique si la chaîne du fichier est convertie en numérique. |
|
|  | [setFormula(boolean value)](#setFormula-boolean-) | Indique si le texte est une formule s'il commence par "=","Indique si la chaîne du fichier est convertie en numérique. |
|
|  | [getConvertNumericData()](#getConvertNumericData--) | Indique si la chaîne du fichier est convertie en date. |
|
|  | [setConvertNumericData(boolean value)](#setConvertNumericData-boolean-) | Indique si la chaîne du fichier est convertie en date. |
|
|  | [getConvertDateTimeData()](#getConvertDateTimeData--) | Indique si la chaîne dans le fichier est convertie en date. |
|
|  | [setConvertDateTimeData(boolean value)](#setConvertDateTimeData-boolean-) | Indique si la chaîne dans le fichier est convertie en date. |
|
|  | [getEncoding()](#getEncoding--) | Encodage. |
|
| [getEncodingInternal()](#getEncodingInternal--) |  |
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Encodage. |
|
| [setEncodingInternal(System.Text.Encoding value)](#setEncodingInternal-com.aspose.ms.System.Text.Encoding-) |  |
### CsvLoadOptions() {#CsvLoadOptions--}
```
public CsvLoadOptions()
```


Initialise une nouvelle instance de la classe [CsvLoadOptions](../../com.groupdocs.conversion.options.load/csvloadoptions).


### getSeparator() {#getSeparator--}
```
public final char getSeparator()
```


Délimiteur d'un fichier Csv.


**Returns:**
char
### setSeparator(char value) {#setSeparator-char-}
```
public final void setSeparator(char value)
```


Délimiteur d'un fichier Csv.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | char |  |

### isMultiEncoded() {#isMultiEncoded--}
```
public final boolean isMultiEncoded()
```


Vrai signifie que le fichier contient plusieurs encodages.


**Returns:**
booléen
### setMultiEncoded(boolean value) {#setMultiEncoded-boolean-}
```
public final void setMultiEncoded(boolean value)
```


Vrai signifie que le fichier contient plusieurs encodages.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### hasFormula() {#hasFormula--}
```
public final boolean hasFormula()
```


Indique si le texte est une formule s'il commence par "=","Indique si la chaîne du fichier est convertie en numérique.


**Returns:**
booléen
### setFormula(boolean value) {#setFormula-boolean-}
```
public final void setFormula(boolean value)
```


Indique si le texte est une formule s'il commence par "=","Indique si la chaîne du fichier est convertie en numérique.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getConvertNumericData() {#getConvertNumericData--}
```
public final boolean getConvertNumericData()
```


Indique si la chaîne dans le fichier est convertie en numérique. La valeur par défaut est True.


**Returns:**
booléen
### setConvertNumericData(boolean value) {#setConvertNumericData-boolean-}
```
public final void setConvertNumericData(boolean value)
```


Indique si la chaîne dans le fichier est convertie en numérique. La valeur par défaut est True.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getConvertDateTimeData() {#getConvertDateTimeData--}
```
public final boolean getConvertDateTimeData()
```


Indique si la chaîne dans le fichier est convertie en date. La valeur par défaut est True.


**Returns:**
booléen
### setConvertDateTimeData(boolean value) {#setConvertDateTimeData-boolean-}
```
public final void setConvertDateTimeData(boolean value)
```


Indique si la chaîne dans le fichier est convertie en date. La valeur par défaut est True.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Encodage. La valeur par défaut est Encoding.Default.


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


Encodage. La valeur par défaut est Encoding.Default.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.nio.charset.Charset |  |

### setEncodingInternal(System.Text.Encoding value) {#setEncodingInternal-com.aspose.ms.System.Text.Encoding-}
```
public void setEncodingInternal(System.Text.Encoding value)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | com.aspose.ms.System.Text.Encoding |  |

