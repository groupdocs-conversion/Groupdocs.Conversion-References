---
title: "SpreadsheetDocumentInfo"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Содержит метаданные документа Spreadsheet"
type: docs
weight: 39
url: /ru/nodejs-java/com.groupdocs.conversion.contracts.documentinfo/spreadsheetdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class SpreadsheetDocumentInfo extends DocumentInfo
```

Содержит метаданные документа Spreadsheet
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [SpreadsheetDocumentInfo(Workbook spreadsheet, boolean isPasswordProtected, FileType format, long size)](#SpreadsheetDocumentInfo-com.aspose.cells.Workbook-boolean-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getTitle()](#getTitle--) | Получает заголовок |
| [getWorksheetsCount()](#getWorksheetsCount--) | Получает количество листов |
| [getAuthor()](#getAuthor--) | Получает автора |
| [isPasswordProtected()](#isPasswordProtected--) | Получает, защищён ли документ паролем |
| [getWorksheets()](#getWorksheets--) | Имена листов |
| [setWorksheets(List<String> worksheets)](#setWorksheets-java.util.List-java.lang.String--) |  |
### SpreadsheetDocumentInfo(Workbook spreadsheet, boolean isPasswordProtected, FileType format, long size) {#SpreadsheetDocumentInfo-com.aspose.cells.Workbook-boolean-com.groupdocs.conversion.filetypes.FileType-long-}
```
public SpreadsheetDocumentInfo(Workbook spreadsheet, boolean isPasswordProtected, FileType format, long size)
```


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| spreadsheet | com.aspose.cells.Workbook |  |
| isPasswordProtected | boolean |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| размер | long |  |

### getTitle() {#getTitle--}
```
public String getTitle()
```


Получает заголовок

**Returns:**
java.lang.String - заголовок
### getWorksheetsCount() {#getWorksheetsCount--}
```
public int getWorksheetsCount()
```


Получает количество листов

**Returns:**
int - количество листов
### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


Получает автора

**Returns:**
java.lang.String - автор
### isPasswordProtected() {#isPasswordProtected--}
```
public boolean isPasswordProtected()
```


Получает, защищён ли документ паролем

**Returns:**
boolean - true если документ защищён паролем
### getWorksheets() {#getWorksheets--}
```
public List<String> getWorksheets()
```


Имена листов

**Returns:**
java.util.List<java.lang.String>
### setWorksheets(List<String> worksheets) {#setWorksheets-java.util.List-java.lang.String--}
```
public void setWorksheets(List<String> worksheets)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| worksheets | java.util.List<java.lang.String> |  |

