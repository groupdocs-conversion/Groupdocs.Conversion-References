---
title: "SpreadsheetConvertOptions"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Параметры конвертации в тип файла Spreadsheet."
type: docs
weight: 40
url: /ru/nodejs-java/com.groupdocs.conversion.options.convert/spreadsheetconvertoptions/
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
| [SpreadsheetConvertOptions()](#SpreadsheetConvertOptions--) | Инициализирует новый экземпляр класса [SpreadsheetConvertOptions](../../com.groupdocs.conversion.options.convert/spreadsheetconvertoptions). |
## Методы

| Метод | Описание |
| --- | --- |
| [getPassword()](#getPassword--) | Установите это свойство, если вы хотите защитить преобразованный документ паролем. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Установите это свойство, если вы хотите защитить преобразованный документ паролем. |
| [getZoom()](#getZoom--) | Указывает уровень масштабирования в процентах. |
| [setZoom(int value)](#setZoom-int-) | Указывает уровень масштабирования в процентах. |
### SpreadsheetConvertOptions() {#SpreadsheetConvertOptions--}
```
public SpreadsheetConvertOptions()
```


Инициализирует новый экземпляр класса [SpreadsheetConvertOptions](../../com.groupdocs.conversion.options.convert/spreadsheetconvertoptions).

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Установите это свойство, если вы хотите защитить преобразованный документ паролем.

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Установите это свойство, если вы хотите защитить преобразованный документ паролем.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getZoom() {#getZoom--}
```
public final int getZoom()
```


Указывает уровень масштабирования в процентах. По умолчанию 100.

**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


Указывает уровень масштабирования в процентах. По умолчанию 100.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

