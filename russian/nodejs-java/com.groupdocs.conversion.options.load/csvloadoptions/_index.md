---
title: "CsvLoadOptions"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Параметры загрузки документов Csv."
type: docs
weight: 14
url: /ru/nodejs-java/com.groupdocs.conversion.options.load/csvloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions), [com.groupdocs.conversion.options.load.SpreadsheetLoadOptions](../../com.groupdocs.conversion.options.load/spreadsheetloadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class CsvLoadOptions extends SpreadsheetLoadOptions implements Serializable
```

Параметры загрузки документов Csv.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [CsvLoadOptions()](#CsvLoadOptions--) | Инициализирует новый экземпляр класса [CsvLoadOptions](../../com.groupdocs.conversion.options.load/csvloadoptions). |
## Методы

| Метод | Описание |
| --- | --- |
| [getSeparator()](#getSeparator--) | Разделитель CSV‑файла. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | Разделитель CSV‑файла. |
| [setSeparator(char value)](#setSeparator-char-) | Разделитель CSV‑файла. |
| [isMultiEncoded()](#isMultiEncoded--) | True означает, что файл содержит несколько кодировок. |
| [setMultiEncoded(boolean value)](#setMultiEncoded-boolean-) | True означает, что файл содержит несколько кодировок. |
| [hasFormula()](#hasFormula--) | Указывает, является ли текст формулой, если он начинается с "=". |
| [setFormula(boolean value)](#setFormula-boolean-) | Указывает, является ли текст формулой, если он начинается с "=". |
| [getConvertNumericData()](#getConvertNumericData--) | Указывает, преобразуется ли строка в файле в числовое значение. |
| [setConvertNumericData(boolean value)](#setConvertNumericData-boolean-) | Указывает, преобразуется ли строка в файле в числовое значение. |
| [getConvertDateTimeData()](#getConvertDateTimeData--) | Указывает, преобразуется ли строка в файле в дату. |
| [setConvertDateTimeData(boolean value)](#setConvertDateTimeData-boolean-) | Указывает, преобразуется ли строка в файле в дату. |
| [getEncoding()](#getEncoding--) | Кодировка. |
| [getEncodingInternal()](#getEncodingInternal--) |  |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Кодировка. |
| [setEncoding(String charsetName)](#setEncoding-java.lang.String-) | Получает или задает кодировку, которая будет использоваться при загрузке документа Txt. |
| [setEncodingInternal(System.Text.Encoding value)](#setEncodingInternal-com.aspose.ms.System.Text.Encoding-) |  |
### CsvLoadOptions() {#CsvLoadOptions--}
```
public CsvLoadOptions()
```


Инициализирует новый экземпляр класса [CsvLoadOptions](../../com.groupdocs.conversion.options.load/csvloadoptions).

### getSeparator() {#getSeparator--}
```
public final char getSeparator()
```


Разделитель CSV‑файла.

**Returns:**
char
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```


Разделитель CSV‑файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setSeparator(char value) {#setSeparator-char-}
```
public final void setSeparator(char value)
```


Разделитель CSV‑файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | char |  |

### isMultiEncoded() {#isMultiEncoded--}
```
public final boolean isMultiEncoded()
```


True означает, что файл содержит несколько кодировок.

**Returns:**
boolean
### setMultiEncoded(boolean value) {#setMultiEncoded-boolean-}
```
public final void setMultiEncoded(boolean value)
```


True означает, что файл содержит несколько кодировок.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### hasFormula() {#hasFormula--}
```
public final boolean hasFormula()
```


Указывает, является ли текст формулой, если он начинается с "=".

**Returns:**
boolean
### setFormula(boolean value) {#setFormula-boolean-}
```
public final void setFormula(boolean value)
```


Указывает, является ли текст формулой, если он начинается с "=".

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getConvertNumericData() {#getConvertNumericData--}
```
public final boolean getConvertNumericData()
```


Указывает, преобразуется ли строка в файле в числовое значение. По умолчанию True.

**Returns:**
boolean
### setConvertNumericData(boolean value) {#setConvertNumericData-boolean-}
```
public final void setConvertNumericData(boolean value)
```


Указывает, преобразуется ли строка в файле в числовое значение. По умолчанию True.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getConvertDateTimeData() {#getConvertDateTimeData--}
```
public final boolean getConvertDateTimeData()
```


Указывает, преобразуется ли строка в файле в дату. По умолчанию True.

**Returns:**
boolean
### setConvertDateTimeData(boolean value) {#setConvertDateTimeData-boolean-}
```
public final void setConvertDateTimeData(boolean value)
```


Указывает, преобразуется ли строка в файле в дату. По умолчанию True.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Кодировка. По умолчанию Encoding.Default.

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


Кодировка. По умолчанию Encoding.Default.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.nio.charset.Charset |  |

### setEncoding(String charsetName) {#setEncoding-java.lang.String-}
```
public final void setEncoding(String charsetName)
```


Получает или задает кодировку, которая будет использоваться при загрузке документа Txt. Может быть null. По умолчанию — null.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| charsetName | java.lang.String |  |

### setEncodingInternal(System.Text.Encoding value) {#setEncodingInternal-com.aspose.ms.System.Text.Encoding-}
```
public void setEncodingInternal(System.Text.Encoding value)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | com.aspose.ms.System.Text.Encoding |  |

