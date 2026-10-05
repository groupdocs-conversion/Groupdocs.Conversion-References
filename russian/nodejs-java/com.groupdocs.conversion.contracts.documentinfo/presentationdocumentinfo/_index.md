---
title: "PresentationDocumentInfo"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Содержит метаданные документа Presentation"
type: docs
weight: 34
url: /ru/nodejs-java/com.groupdocs.conversion.contracts.documentinfo/presentationdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class PresentationDocumentInfo extends DocumentInfo
```

Содержит метаданные документа Presentation
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PresentationDocumentInfo(Presentation presentation, FileType format, long size, boolean isPasswordProtected)](#PresentationDocumentInfo-com.aspose.slides.Presentation-com.groupdocs.conversion.filetypes.FileType-long-boolean-) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getTitle()](#getTitle--) | Получает заголовок |
| [setTitle(String title)](#setTitle-java.lang.String-) | Устанавливает заголовок |
| [getAuthor()](#getAuthor--) | Получает автора |
| [setAuthor(String author)](#setAuthor-java.lang.String-) | Устанавливает автора |
| [isPasswordProtected()](#isPasswordProtected--) | Получает, защищён ли документ паролем |
### PresentationDocumentInfo(Presentation presentation, FileType format, long size, boolean isPasswordProtected) {#PresentationDocumentInfo-com.aspose.slides.Presentation-com.groupdocs.conversion.filetypes.FileType-long-boolean-}
```
public PresentationDocumentInfo(Presentation presentation, FileType format, long size, boolean isPasswordProtected)
```


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| презентация | com.aspose.slides.Presentation |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| размер | long |  |
| isPasswordProtected | boolean |  |

### getTitle() {#getTitle--}
```
public String getTitle()
```


Получает заголовок

**Returns:**
java.lang.String - заголовок
### setTitle(String title) {#setTitle-java.lang.String-}
```
public void setTitle(String title)
```


Устанавливает заголовок

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| заголовок | java.lang.String | заголовок |

### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


Получает автора

**Returns:**
java.lang.String - автор
### setAuthor(String author) {#setAuthor-java.lang.String-}
```
public void setAuthor(String author)
```


Устанавливает автора

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| автор | java.lang.String | автор |

### isPasswordProtected() {#isPasswordProtected--}
```
public boolean isPasswordProtected()
```


Получает, защищён ли документ паролем

**Returns:**
boolean - `true`, если документ защищён паролем
