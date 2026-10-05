---
title: "TxtLoadOptions"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Параметры загрузки документов Txt."
type: docs
weight: 38
url: /ru/nodejs-java/com.groupdocs.conversion.options.load/txtloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class TxtLoadOptions extends LoadOptions implements Serializable
```

Параметры загрузки документов Txt.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TxtLoadOptions()](#TxtLoadOptions--) | Инициализирует новый экземпляр класса [TxtLoadOptions](../../com.groupdocs.conversion.options.load/txtloadoptions). |
## Методы

| Метод | Описание |
| --- | --- |
| [getFormat()](#getFormat--) |  |
| [getDetectNumberingWithWhitespaces()](#getDetectNumberingWithWhitespaces--) | Позволяет указать, как распознавать элементы нумерованных списков при конвертации простого текстового документа. |
| [setDetectNumberingWithWhitespaces(boolean value)](#setDetectNumberingWithWhitespaces-boolean-) | Позволяет указать, как распознавать элементы нумерованных списков при конвертации простого текстового документа. |
| [getTrailingSpacesOptions()](#getTrailingSpacesOptions--) | Получает или задает предпочтительный вариант обработки конечных пробелов. |
| [setTrailingSpacesOptions(TxtTrailingSpacesOptions value)](#setTrailingSpacesOptions-com.groupdocs.conversion.options.load.TxtTrailingSpacesOptions-) | Получает или задает предпочтительный вариант обработки конечных пробелов. |
| [getLeadingSpacesOptions()](#getLeadingSpacesOptions--) | Получает или задает предпочтительный вариант обработки начальных пробелов. |
| [setLeadingSpacesOptions(TxtLeadingSpacesOptions value)](#setLeadingSpacesOptions-com.groupdocs.conversion.options.load.TxtLeadingSpacesOptions-) | Получает или задает предпочтительный вариант обработки начальных пробелов. |
| [getEncoding()](#getEncoding--) | Получает или задает кодировку, которая будет использоваться при загрузке документа Txt. |
| [getEncodingInternal()](#getEncodingInternal--) |  |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Получает или задает кодировку, которая будет использоваться при загрузке документа Txt. |
| [setEncoding(String charsetName)](#setEncoding-java.lang.String-) | Получает или задает кодировку, которая будет использоваться при загрузке документа Txt. |
### TxtLoadOptions() {#TxtLoadOptions--}
```
public TxtLoadOptions()
```


Инициализирует новый экземпляр класса [TxtLoadOptions](../../com.groupdocs.conversion.options.load/txtloadoptions).

### getFormat() {#getFormat--}
```
public WordProcessingFileType getFormat()
```


Тип файла входного документа

**Returns:**
[WordProcessingFileType](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype)
### getDetectNumberingWithWhitespaces() {#getDetectNumberingWithWhitespaces--}
```
public final boolean getDetectNumberingWithWhitespaces()
```


Позволяет указать, как распознавать элементы нумерованных списков при конвертации простого текстового документа. Значение по умолчанию — true.

--------------------

Если эта опция установлена в false, алгоритм распознавания списков обнаруживает абзацы списков, когда номера списков заканчиваются точкой, правой скобкой или символами маркеров (например, "\\u2022", "\*", "-" или "o").

Если эта опция установлена в true, пробелы также используются в качестве разделителей номеров списков: алгоритм распознавания списков для арабской нумерации (1., 1.1.2.) использует как пробелы, так и точку (".") символы.

**Returns:**
boolean
### setDetectNumberingWithWhitespaces(boolean value) {#setDetectNumberingWithWhitespaces-boolean-}
```
public final void setDetectNumberingWithWhitespaces(boolean value)
```


Позволяет указать, как распознавать элементы нумерованных списков при конвертации простого текстового документа. Значение по умолчанию — true.

--------------------

Если эта опция установлена в false, алгоритм распознавания списков обнаруживает абзацы списков, когда номера списков заканчиваются точкой, правой скобкой или символами маркеров (например, "\\u2022", "\*", "-" или "o").

Если эта опция установлена в true, пробелы также используются в качестве разделителей номеров списков: алгоритм распознавания списков для арабской нумерации (1., 1.1.2.) использует как пробелы, так и точку (".") символы.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getTrailingSpacesOptions() {#getTrailingSpacesOptions--}
```
public final TxtTrailingSpacesOptions getTrailingSpacesOptions()
```


Получает или задает предпочтительный вариант обработки конечных пробелов. Значение по умолчанию — [TxtTrailingSpacesOptions.Trim](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions\#Trim).

**Returns:**
[TxtTrailingSpacesOptions](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions)
### setTrailingSpacesOptions(TxtTrailingSpacesOptions value) {#setTrailingSpacesOptions-com.groupdocs.conversion.options.load.TxtTrailingSpacesOptions-}
```
public final void setTrailingSpacesOptions(TxtTrailingSpacesOptions value)
```


Получает или задает предпочтительный вариант обработки конечных пробелов. Значение по умолчанию — [TxtTrailingSpacesOptions.Trim](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions\#Trim).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TxtTrailingSpacesOptions](../../com.groupdocs.conversion.options.load/txttrailingspacesoptions) |  |

### getLeadingSpacesOptions() {#getLeadingSpacesOptions--}
```
public final TxtLeadingSpacesOptions getLeadingSpacesOptions()
```


Получает или задает предпочтительный вариант обработки начальных пробелов. Значение по умолчанию — [TxtLeadingSpacesOptions.ConvertToIndent](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions\#ConvertToIndent).

**Returns:**
[TxtLeadingSpacesOptions](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions)
### setLeadingSpacesOptions(TxtLeadingSpacesOptions value) {#setLeadingSpacesOptions-com.groupdocs.conversion.options.load.TxtLeadingSpacesOptions-}
```
public final void setLeadingSpacesOptions(TxtLeadingSpacesOptions value)
```


Получает или задает предпочтительный вариант обработки начальных пробелов. Значение по умолчанию — [TxtLeadingSpacesOptions.ConvertToIndent](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions\#ConvertToIndent).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TxtLeadingSpacesOptions](../../com.groupdocs.conversion.options.load/txtleadingspacesoptions) |  |

### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Получает или задает кодировку, которая будет использоваться при загрузке документа Txt. Может быть null. По умолчанию — null.

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


Получает или задает кодировку, которая будет использоваться при загрузке документа Txt. Может быть null. По умолчанию — null.

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

