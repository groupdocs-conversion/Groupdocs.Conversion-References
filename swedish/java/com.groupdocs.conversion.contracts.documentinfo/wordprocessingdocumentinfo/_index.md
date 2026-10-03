---
title: "WordProcessingDocumentInfo"
second_title: "GroupDocs.Conversion för Java API-referens"
description: "Innehåller metadata för Wordprocessing-dokument"
type: docs
weight: 45
url: /sv/java/com.groupdocs.conversion.contracts.documentinfo/wordprocessingdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class WordProcessingDocumentInfo extends DocumentInfo
```

Innehåller metadata för Wordprocessing-dokument

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [WordProcessingDocumentInfo(Document wordprocessing, boolean isPasswordProtected, FileType format, long size)](#WordProcessingDocumentInfo-com.aspose.words.Document-boolean-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getWords()](#getWords--) | Hämtar antalet ord |
|
|  | [getLines()](#getLines--) | Hämtar antalet rader |
|
|  | [getTitle()](#getTitle--) | Hämtar titel |
|
|  | [getAuthor()](#getAuthor--) | Hämtar författare |
|
|  | [isPasswordProtected()](#isPasswordProtected--) | Hämtar om dokumentet är lösenordsskyddat |
|
|  | [getTableOfContents()](#getTableOfContents--) | Innehållsförteckning |
|
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
| storlek | long |  |

### getWords() {#getWords--}
```
public int getWords()
```


Hämtar antalet ord


**Returns:**
int - antal ord

### getLines() {#getLines--}
```
public int getLines()
```


Hämtar antalet rader


**Returns:**
int - antal rader

### getTitle() {#getTitle--}
```
public String getTitle()
```


Hämtar titel


**Returns:**
java.lang.String - titel

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

