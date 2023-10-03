---
title: PresentationDocumentInfo
second_title: GroupDocs.Conversion for Java API Reference
description: Contains Presentation document metadata
type: docs
weight: 31
url: /java/com.groupdocs.conversion.contracts.documentinfo/presentationdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class PresentationDocumentInfo extends DocumentInfo
```

Contains Presentation document metadata
## Constructors

| Constructor | Description |
| --- | --- |
| [PresentationDocumentInfo(Presentation presentation, FileType format, long size, boolean isPasswordProtected)](#PresentationDocumentInfo-com.aspose.slides.Presentation-com.groupdocs.conversion.filetypes.FileType-long-boolean-) |  |
## Methods

| Method | Description |
| --- | --- |
| [getTitle()](#getTitle--) | Gets title |
| [setTitle(String title)](#setTitle-java.lang.String-) | Sets title |
| [getAuthor()](#getAuthor--) | Gets author |
| [setAuthor(String author)](#setAuthor-java.lang.String-) | Sets author |
| [isPasswordProtected()](#isPasswordProtected--) | Gets is the document password protected |
### PresentationDocumentInfo(Presentation presentation, FileType format, long size, boolean isPasswordProtected) {#PresentationDocumentInfo-com.aspose.slides.Presentation-com.groupdocs.conversion.filetypes.FileType-long-boolean-}
```
public PresentationDocumentInfo(Presentation presentation, FileType format, long size, boolean isPasswordProtected)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| presentation | com.aspose.slides.Presentation |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |
| isPasswordProtected | boolean |  |

### getTitle() {#getTitle--}
```
public String getTitle()
```


Gets title

**Returns:**
java.lang.String - title
### setTitle(String title) {#setTitle-java.lang.String-}
```
public void setTitle(String title)
```


Sets title

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| title | java.lang.String | title |

### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


Gets author

**Returns:**
java.lang.String - author
### setAuthor(String author) {#setAuthor-java.lang.String-}
```
public void setAuthor(String author)
```


Sets author

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| author | java.lang.String | author |

### isPasswordProtected() {#isPasswordProtected--}
```
public boolean isPasswordProtected()
```


Gets is the document password protected

**Returns:**
boolean - `true` if document is password protected
