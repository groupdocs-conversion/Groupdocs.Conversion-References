---
title: "WordProcessingDocumentInfo"
second_title: "GroupDocs.Conversion för Node.js via Java API-referens"
description: "Innehåller Wordprocessing-dokumentmetadata"
type: docs
weight: 48
url: /sv/nodejs-java/com.groupdocs.conversion.contracts.documentinfo/wordprocessingdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class WordProcessingDocumentInfo extends DocumentInfo
```

Innehåller Wordprocessing-dokumentmetadata
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [WordProcessingDocumentInfo(Document wordprocessing, boolean isPasswordProtected, FileType format, long size)](#WordProcessingDocumentInfo-com.aspose.words.Document-boolean-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getWords()](#getWords--) | Hämtar ordantal |
| [getLines()](#getLines--) | Hämtar radantal |
| [getTitle()](#getTitle--) | Hämtar titel |
| [getAuthor()](#getAuthor--) | Hämtar författare |
| [isPasswordProtected()](#isPasswordProtected--) | Hämtar om dokumentet är lösenordsskyddat |
| [getTableOfContents()](#getTableOfContents--) | Innehållsförteckning |
### WordProcessingDocumentInfo(Document wordprocessing, boolean isPasswordProtected, FileType format, long size) {#WordProcessingDocumentInfo-com.aspose.words.Document-boolean-com.groupdocs.conversion.filetypes.FileType-long-}
```
public WordProcessingDocumentInfo(Document wordprocessing, boolean isPasswordProtected, FileType format, long size)
```


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| wordprocessing | com.aspose.words.Document |  |
| isPasswordProtected | boolean |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |

### getWords() {#getWords--}
```
public int getWords()
```


Hämtar ordantal

**Returns:**
int - ordantal
### getLines() {#getLines--}
```
public int getLines()
```


Hämtar radantal

**Returns:**
int - radantal
### getTitle() {#getTitle--}
```
public String getTitle()
```


Hämtar titel

**Returns:**
java.lang.String - title
### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


Hämtar författare

**Returns:**
java.lang.String - författare
### isPasswordProtected() {#isPasswordProtected--}
```
public boolean isPasswordProtected()
```


Hämtar om dokumentet är lösenordsskyddat

**Returns:**
boolean - `true` om dokumentet är lösenordsskyddat
### getTableOfContents() {#getTableOfContents--}
```
public List<TableOfContentsItem> getTableOfContents()
```


Innehållsförteckning

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem> - Innehållsförteckning
