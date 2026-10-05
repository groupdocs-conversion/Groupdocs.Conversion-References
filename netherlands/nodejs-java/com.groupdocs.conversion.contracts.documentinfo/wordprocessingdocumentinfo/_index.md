---
title: "WordProcessingDocumentInfo"
second_title: "GroupDocs.Conversion for Node.js via Java API-referentie"
description: "Bevat metadata van Wordprocessing-document"
type: docs
weight: 48
url: /nl/nodejs-java/com.groupdocs.conversion.contracts.documentinfo/wordprocessingdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class WordProcessingDocumentInfo extends DocumentInfo
```

Bevat metadata van Wordprocessing-document
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [WordProcessingDocumentInfo(Document wordprocessing, boolean isPasswordProtected, FileType format, long size)](#WordProcessingDocumentInfo-com.aspose.words.Document-boolean-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getWords()](#getWords--) | Haalt aantal woorden op |
| [getLines()](#getLines--) | Haalt het aantal regels op |
| [getTitle()](#getTitle--) | Haalt titel op |
| [getAuthor()](#getAuthor--) | Haalt auteur op |
| [isPasswordProtected()](#isPasswordProtected--) | Haalt op of document met wachtwoord beveiligd is |
| [getTableOfContents()](#getTableOfContents--) | Inhoudsopgave |
### WordProcessingDocumentInfo(Document wordprocessing, boolean isPasswordProtected, FileType format, long size) {#WordProcessingDocumentInfo-com.aspose.words.Document-boolean-com.groupdocs.conversion.filetypes.FileType-long-}
```
public WordProcessingDocumentInfo(Document wordprocessing, boolean isPasswordProtected, FileType format, long size)
```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| tekstverwerking | com.aspose.words.Document |  |
| isPasswordProtected | boolean |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |

### getWords() {#getWords--}
```
public int getWords()
```


Haalt aantal woorden op

**Returns:**
int - aantal woorden
### getLines() {#getLines--}
```
public int getLines()
```


Haalt het aantal regels op

**Returns:**
int - aantal regels
### getTitle() {#getTitle--}
```
public String getTitle()
```


Haalt titel op

**Returns:**
java.lang.String - titel
### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


Haalt auteur op

**Returns:**
java.lang.String - auteur
### isPasswordProtected() {#isPasswordProtected--}
```
public boolean isPasswordProtected()
```


Haalt op of document met wachtwoord beveiligd is

**Returns:**
boolean - `true` als het document met wachtwoord beveiligd is
### getTableOfContents() {#getTableOfContents--}
```
public List<TableOfContentsItem> getTableOfContents()
```


Inhoudsopgave

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem> - inhoudsopgave
