---
title: "SpreadsheetConvertOptions"
second_title: "Справочник API GroupDocs.Conversion for Java"
description: "Параметры конвертации в тип файла Spreadsheet."
type: docs
weight: 40
url: /ru/java/com.groupdocs.conversion.options.convert/spreadsheetconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable
```
public class SpreadsheetConvertOptions extends CommonConvertOptions<SpreadsheetFileType> implements Serializable
```

Параметры конвертации в тип файла Spreadsheet.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [SpreadsheetConvertOptions()](#SpreadsheetConvertOptions--) | Инициализирует новый экземпляр класса [SpreadsheetConvertOptions](../../com.groupdocs.conversion.options.convert/spreadsheetconvertoptions). |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getPassword()](#getPassword--) | Установите это свойство, если хотите защитить конвертированный документ паролем. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Установите это свойство, если хотите защитить конвертированный документ паролем. |
|
|  | [getZoom()](#getZoom--) | Указывает уровень масштабирования в процентах. |
|
|  | [setZoom(int value)](#setZoom-int-) | Указывает уровень масштабирования в процентах. |
|
|  | [getSeparator()](#getSeparator--) | Указывает разделитель, который будет использоваться при конвертации в форматы с разделителями |
|
| [setSeparator(char separator)](#setSeparator-char-) |  |
| [setFormat(FileType value)](#setFormat-com.groupdocs.conversion.filetypes.FileType-) |  |
### SpreadsheetConvertOptions() {#SpreadsheetConvertOptions--}
```
public SpreadsheetConvertOptions()
```


Инициализирует новый экземпляр класса [SpreadsheetConvertOptions](../../com.groupdocs.conversion.options.convert/spreadsheetconvertoptions).


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Установите это свойство, если хотите защитить конвертированный документ паролем.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Установите это свойство, если хотите защитить конвертированный документ паролем.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getZoom() {#getZoom--}
```
public final int getZoom()
```


Указывает уровень масштабирования в процентах. По умолчанию — 100.


**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


Указывает уровень масштабирования в процентах. По умолчанию — 100.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getSeparator() {#getSeparator--}
```
public char getSeparator()
```


Указывает разделитель, который будет использоваться при конвертации в форматы с разделителями


**Returns:**
char
### setSeparator(char separator) {#setSeparator-char-}
```
public void setSeparator(char separator)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| разделитель | char |  |

### setFormat(FileType value) {#setFormat-com.groupdocs.conversion.filetypes.FileType-}
```
public void setFormat(FileType value)
```


Желаемый тип файла, в который должен быть конвертирован входной документ.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |

