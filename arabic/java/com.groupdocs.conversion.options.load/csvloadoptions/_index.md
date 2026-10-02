---
title: "CsvLoadOptions"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "خيارات تحميل مستندات CSV."
type: docs
weight: 13
url: /ar/java/com.groupdocs.conversion.options.load/csvloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions), [com.groupdocs.conversion.options.load.SpreadsheetLoadOptions](../../com.groupdocs.conversion.options.load/spreadsheetloadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class CsvLoadOptions extends SpreadsheetLoadOptions implements Serializable
```

خيارات تحميل مستندات CSV.

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [CsvLoadOptions()](#CsvLoadOptions--) | يُنشئ مثيلًا جديدًا من الفئة [CsvLoadOptions](../../com.groupdocs.conversion.options.load/csvloadoptions). |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getSeparator()](#getSeparator--) | فاصل ملف Csv. |
|
|  | [setSeparator(char value)](#setSeparator-char-) | فاصل ملف Csv. |
|
|  | [isMultiEncoded()](#isMultiEncoded--) | يعني True أن الملف يحتوي على عدة ترميزات. |
|
|  | [setMultiEncoded(boolean value)](#setMultiEncoded-boolean-) | يعني True أن الملف يحتوي على عدة ترميزات. |
|
|  | [hasFormula()](#hasFormula--) | يشير إلى ما إذا كان النص صيغة إذا بدأ بـ "=". |
|
|  | [setFormula(boolean value)](#setFormula-boolean-) | يشير إلى ما إذا كان النص صيغة إذا بدأ بـ "=". |
|
|  | [getConvertNumericData()](#getConvertNumericData--) | يشير إلى ما إذا كان النص في الملف يُحوَّل إلى رقم. |
|
|  | [setConvertNumericData(boolean value)](#setConvertNumericData-boolean-) | يشير إلى ما إذا كان النص في الملف يُحوَّل إلى رقم. |
|
|  | [getConvertDateTimeData()](#getConvertDateTimeData--) | يشير إلى ما إذا كان النص في الملف يُحوَّل إلى تاريخ. |
|
|  | [setConvertDateTimeData(boolean value)](#setConvertDateTimeData-boolean-) | يشير إلى ما إذا كان النص في الملف يُحوَّل إلى تاريخ. |
|
|  | [getEncoding()](#getEncoding--) | الترميز. |
|
| [getEncodingInternal()](#getEncodingInternal--) |  |
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | الترميز. |
|
| [setEncodingInternal(System.Text.Encoding value)](#setEncodingInternal-com.aspose.ms.System.Text.Encoding-) |  |
### CsvLoadOptions() {#CsvLoadOptions--}
```
public CsvLoadOptions()
```


يُنشئ مثيلًا جديدًا من الفئة [CsvLoadOptions](../../com.groupdocs.conversion.options.load/csvloadoptions).


### getSeparator() {#getSeparator--}
```
public final char getSeparator()
```


فاصل ملف Csv.


**Returns:**
حرف
### setSeparator(char value) {#setSeparator-char-}
```
public final void setSeparator(char value)
```


فاصل ملف Csv.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | حرف |  |

### isMultiEncoded() {#isMultiEncoded--}
```
public final boolean isMultiEncoded()
```


يعني True أن الملف يحتوي على عدة ترميزات.


**Returns:**
منطقي
### setMultiEncoded(boolean value) {#setMultiEncoded-boolean-}
```
public final void setMultiEncoded(boolean value)
```


يعني True أن الملف يحتوي على عدة ترميزات.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | منطقي |  |

### hasFormula() {#hasFormula--}
```
public final boolean hasFormula()
```


يشير إلى ما إذا كان النص صيغة إذا بدأ بـ "=".


**Returns:**
منطقي
### setFormula(boolean value) {#setFormula-boolean-}
```
public final void setFormula(boolean value)
```


يشير إلى ما إذا كان النص صيغة إذا بدأ بـ "=".


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | منطقي |  |

### getConvertNumericData() {#getConvertNumericData--}
```
public final boolean getConvertNumericData()
```


يشير إلى ما إذا كان السلسلة في الملف تُحوَّل إلى رقمية. القيمة الافتراضية هي True.


**Returns:**
منطقي
### setConvertNumericData(boolean value) {#setConvertNumericData-boolean-}
```
public final void setConvertNumericData(boolean value)
```


يشير إلى ما إذا كان السلسلة في الملف تُحوَّل إلى رقمية. القيمة الافتراضية هي True.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | منطقي |  |

### getConvertDateTimeData() {#getConvertDateTimeData--}
```
public final boolean getConvertDateTimeData()
```


يشير إلى ما إذا كان السلسلة في الملف تُحوَّل إلى تاريخ. القيمة الافتراضية هي True.


**Returns:**
منطقي
### setConvertDateTimeData(boolean value) {#setConvertDateTimeData-boolean-}
```
public final void setConvertDateTimeData(boolean value)
```


يشير إلى ما إذا كان السلسلة في الملف تُحوَّل إلى تاريخ. القيمة الافتراضية هي True.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | منطقي |  |

### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


الترميز. القيمة الافتراضية هي Encoding.Default.


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


الترميز. القيمة الافتراضية هي Encoding.Default.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.nio.charset.Charset |  |

### setEncodingInternal(System.Text.Encoding value) {#setEncodingInternal-com.aspose.ms.System.Text.Encoding-}
```
public void setEncodingInternal(System.Text.Encoding value)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | com.aspose.ms.System.Text.Encoding |  |

