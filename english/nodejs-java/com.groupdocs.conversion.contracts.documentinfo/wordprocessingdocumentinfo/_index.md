---
title: WordProcessingDocumentInfo
second_title: GroupDocs.Conversion for Node.js via Java API Reference
description: Contains Wordprocessing document metadata
type: docs
weight: 48
url: /nodejs-java/com.groupdocs.conversion.contracts.documentinfo/wordprocessingdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class WordProcessingDocumentInfo extends DocumentInfo
```

Contains Wordprocessing document metadata
## Constructors

| Constructor | Description |
| --- | --- |
| [WordProcessingDocumentInfo(Document wordprocessing, boolean isPasswordProtected, FileType format, long size)](#WordProcessingDocumentInfo-com.aspose.words.Document-boolean-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Methods

| Method | Description |
| --- | --- |
| [getWords()](#getWords--) | Gets words count |
| [getLines()](#getLines--) | Gets lines count |
| [getTitle()](#getTitle--) | Gets title |
| [getAuthor()](#getAuthor--) | Gets author |
| [isPasswordProtected()](#isPasswordProtected--) | Gets is document password protected |
| [getTableOfContents()](#getTableOfContents--) | Table of contents |
### WordProcessingDocumentInfo(Document wordprocessing, boolean isPasswordProtected, FileType format, long size) {#WordProcessingDocumentInfo-com.aspose.words.Document-boolean-com.groupdocs.conversion.filetypes.FileType-long-}
```
public WordProcessingDocumentInfo(Document wordprocessing, boolean isPasswordProtected, FileType format, long size)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| wordprocessing | com.aspose.words.Document |  |
| isPasswordProtected | boolean |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |

### getWords() {#getWords--}
```
public int getWords()
```


Gets words count

**Returns:**
int - words count
### getLines() {#getLines--}
```
public int getLines()
```


Gets lines count

**Returns:**
int - lines count
### getTitle() {#getTitle--}
```
public String getTitle()
```


Gets title

**Returns:**
java.lang.String - title
### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


Gets author

**Returns:**
java.lang.String - author
### isPasswordProtected() {#isPasswordProtected--}
```
public boolean isPasswordProtected()
```


Gets is document password protected

**Returns:**
boolean - `true` if document is password protected
### getTableOfContents() {#getTableOfContents--}
```
public List<TableOfContentsItem> getTableOfContents()
```


Table of contents

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem> - Table of contents
