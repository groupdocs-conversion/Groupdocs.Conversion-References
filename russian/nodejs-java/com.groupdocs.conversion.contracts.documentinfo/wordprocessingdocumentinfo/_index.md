---
title: "WordProcessingDocumentInfo"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Содержит метаданные документа Wordprocessing"
type: docs
weight: 48
url: /ru/nodejs-java/com.groupdocs.conversion.contracts.documentinfo/wordprocessingdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class WordProcessingDocumentInfo extends DocumentInfo
```

Содержит метаданные документа Wordprocessing
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [WordProcessingDocumentInfo(Document wordprocessing, boolean isPasswordProtected, FileType format, long size)](#WordProcessingDocumentInfo-com.aspose.words.Document-boolean-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getWords()](#getWords--) | Получает количество слов |
| [getLines()](#getLines--) | Получает количество строк |
| [getTitle()](#getTitle--) | Получает заголовок |
| [getAuthor()](#getAuthor--) | Получает автора |
| [isPasswordProtected()](#isPasswordProtected--) | Получает, защищён ли документ паролем |
| [getTableOfContents()](#getTableOfContents--) | Оглавление |
### WordProcessingDocumentInfo(Document wordprocessing, boolean isPasswordProtected, FileType format, long size) {#WordProcessingDocumentInfo-com.aspose.words.Document-boolean-com.groupdocs.conversion.filetypes.FileType-long-}
```
public WordProcessingDocumentInfo(Document wordprocessing, boolean isPasswordProtected, FileType format, long size)
```


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| обработка слов | com.aspose.words.Document |  |
| isPasswordProtected | boolean |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| размер | long |  |

### getWords() {#getWords--}
```
public int getWords()
```


Получает количество слов

**Returns:**
int - количество слов
### getLines() {#getLines--}
```
public int getLines()
```


Получает количество строк

**Returns:**
int - количество строк
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


Получает, защищён ли документ паролем

**Returns:**
boolean - `true`, если документ защищён паролем
### getTableOfContents() {#getTableOfContents--}
```
public List<TableOfContentsItem> getTableOfContents()
```


Оглавление

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem> - Оглавление
