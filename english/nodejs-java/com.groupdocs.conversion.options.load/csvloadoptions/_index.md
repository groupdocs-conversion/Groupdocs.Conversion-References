---
title: CsvLoadOptions
second_title: GroupDocs.Conversion for Node.js via Java API Reference
description: Options for loading Csv documents.
type: docs
weight: 13
url: /nodejs-java/com.groupdocs.conversion.options.load/csvloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions), [com.groupdocs.conversion.options.load.SpreadsheetLoadOptions](../../com.groupdocs.conversion.options.load/spreadsheetloadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class CsvLoadOptions extends SpreadsheetLoadOptions implements Serializable
```

Options for loading Csv documents.
## Constructors

| Constructor | Description |
| --- | --- |
| [CsvLoadOptions()](#CsvLoadOptions--) | Initializes new instance of [CsvLoadOptions](../../com.groupdocs.conversion.options.load/csvloadoptions) class. |
## Methods

| Method | Description |
| --- | --- |
| [getSeparator()](#getSeparator--) | Delimiter of a Csv file. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | Delimiter of a Csv file. |
| [setSeparator(char value)](#setSeparator-char-) | Delimiter of a Csv file. |
| [isMultiEncoded()](#isMultiEncoded--) | True means the file contains several encodings. |
| [setMultiEncoded(boolean value)](#setMultiEncoded-boolean-) | True means the file contains several encodings. |
| [hasFormula()](#hasFormula--) | Indicates whether text is formula if it starts with "=". |
| [setFormula(boolean value)](#setFormula-boolean-) | Indicates whether text is formula if it starts with "=". |
| [getConvertNumericData()](#getConvertNumericData--) | Indicates whether the string in the file is converted to numeric. |
| [setConvertNumericData(boolean value)](#setConvertNumericData-boolean-) | Indicates whether the string in the file is converted to numeric. |
| [getConvertDateTimeData()](#getConvertDateTimeData--) | Indicates whether the string in the file is converted to date. |
| [setConvertDateTimeData(boolean value)](#setConvertDateTimeData-boolean-) | Indicates whether the string in the file is converted to date. |
| [getEncoding()](#getEncoding--) | Encoding. |
| [getEncodingInternal()](#getEncodingInternal--) |  |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Encoding. |
| [setEncoding(String charsetName)](#setEncoding-java.lang.String-) | Gets or sets the encoding that will be used when loading Txt document. |
| [setEncodingInternal(System.Text.Encoding value)](#setEncodingInternal-com.aspose.ms.System.Text.Encoding-) |  |
### CsvLoadOptions() {#CsvLoadOptions--}
```
public CsvLoadOptions()
```


Initializes new instance of [CsvLoadOptions](../../com.groupdocs.conversion.options.load/csvloadoptions) class.

### getSeparator() {#getSeparator--}
```
public final char getSeparator()
```


Delimiter of a Csv file.

**Returns:**
char
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```


Delimiter of a Csv file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setSeparator(char value) {#setSeparator-char-}
```
public final void setSeparator(char value)
```


Delimiter of a Csv file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | char |  |

### isMultiEncoded() {#isMultiEncoded--}
```
public final boolean isMultiEncoded()
```


True means the file contains several encodings.

**Returns:**
boolean
### setMultiEncoded(boolean value) {#setMultiEncoded-boolean-}
```
public final void setMultiEncoded(boolean value)
```


True means the file contains several encodings.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### hasFormula() {#hasFormula--}
```
public final boolean hasFormula()
```


Indicates whether text is formula if it starts with "=".

**Returns:**
boolean
### setFormula(boolean value) {#setFormula-boolean-}
```
public final void setFormula(boolean value)
```


Indicates whether text is formula if it starts with "=".

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getConvertNumericData() {#getConvertNumericData--}
```
public final boolean getConvertNumericData()
```


Indicates whether the string in the file is converted to numeric. Default is True.

**Returns:**
boolean
### setConvertNumericData(boolean value) {#setConvertNumericData-boolean-}
```
public final void setConvertNumericData(boolean value)
```


Indicates whether the string in the file is converted to numeric. Default is True.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getConvertDateTimeData() {#getConvertDateTimeData--}
```
public final boolean getConvertDateTimeData()
```


Indicates whether the string in the file is converted to date. Default is True.

**Returns:**
boolean
### setConvertDateTimeData(boolean value) {#setConvertDateTimeData-boolean-}
```
public final void setConvertDateTimeData(boolean value)
```


Indicates whether the string in the file is converted to date. Default is True.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Encoding. Default is Encoding.Default.

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


Encoding. Default is Encoding.Default.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.nio.charset.Charset |  |

### setEncoding(String charsetName) {#setEncoding-java.lang.String-}
```
public final void setEncoding(String charsetName)
```


Gets or sets the encoding that will be used when loading Txt document. Can be null. Default is null.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| charsetName | java.lang.String |  |

### setEncodingInternal(System.Text.Encoding value) {#setEncodingInternal-com.aspose.ms.System.Text.Encoding-}
```
public void setEncodingInternal(System.Text.Encoding value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.Text.Encoding |  |

