---
title: "PdfDocumentInfo"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Содержит метаданные документа Pdf"
type: docs
weight: 31
url: /ru/nodejs-java/com.groupdocs.conversion.contracts.documentinfo/pdfdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class PdfDocumentInfo extends DocumentInfo
```

Содержит метаданные документа Pdf
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PdfDocumentInfo(Document pdf, FileType format, long size)](#PdfDocumentInfo-com.aspose.pdf.Document-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getVersion()](#getVersion--) | Получает версию |
| [getTitle()](#getTitle--) | Получает заголовок |
| [getAuthor()](#getAuthor--) | Получает автора |
| [isPasswordProtected()](#isPasswordProtected--) | Получает, зашифрован ли |
| [isLandscape()](#isLandscape--) | Получает, имеет ли страница альбомную ориентацию |
| [getHeight()](#getHeight--) | Получает высоту страницы |
| [getWidth()](#getWidth--) | Получает ширину страницы |
| [getTableOfContents()](#getTableOfContents--) | Получает оглавление |
| [setTableOfContents(List<TableOfContentsItem> tableOfContents)](#setTableOfContents-java.util.List-com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem--) | Устанавливает оглавление |
### PdfDocumentInfo(Document pdf, FileType format, long size) {#PdfDocumentInfo-com.aspose.pdf.Document-com.groupdocs.conversion.filetypes.FileType-long-}
```
public PdfDocumentInfo(Document pdf, FileType format, long size)
```


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pdf | com.aspose.pdf.Document |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| размер | long |  |

### getVersion() {#getVersion--}
```
public String getVersion()
```


Получает версию

**Returns:**
java.lang.String - версия
### getTitle() {#getTitle--}
```
public String getTitle()
```


Получает заголовок

**Returns:**
java.lang.String - заголовок
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


Получает, зашифрован ли

**Returns:**
boolean - true если зашифровано
### isLandscape() {#isLandscape--}
```
public boolean isLandscape()
```


Получает, имеет ли страница альбомную ориентацию

**Returns:**
boolean - true если страница в альбомной ориентации
### getHeight() {#getHeight--}
```
public double getHeight()
```


Получает высоту страницы

**Returns:**
double - высота страницы
### getWidth() {#getWidth--}
```
public double getWidth()
```


Получает ширину страницы

**Returns:**
double - ширина страницы
### getTableOfContents() {#getTableOfContents--}
```
public List<TableOfContentsItem> getTableOfContents()
```


Получает оглавление

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem> - Оглавление
### setTableOfContents(List<TableOfContentsItem> tableOfContents) {#setTableOfContents-java.util.List-com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem--}
```
public void setTableOfContents(List<TableOfContentsItem> tableOfContents)
```


Устанавливает оглавление

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| tableOfContents | java.util.List<com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem> | Оглавление |

