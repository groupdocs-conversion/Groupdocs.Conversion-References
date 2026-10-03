---
title: "WordProcessingDocumentInfo"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Enthält Metadaten des Wordprocessing-Dokuments"
type: docs
weight: 45
url: /de/java/com.groupdocs.conversion.contracts.documentinfo/wordprocessingdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class WordProcessingDocumentInfo extends DocumentInfo
```

Enthält Metadaten des Wordprocessing-Dokuments

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [WordProcessingDocumentInfo(Document wordprocessing, boolean isPasswordProtected, FileType format, long size)](#WordProcessingDocumentInfo-com.aspose.words.Document-boolean-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getWords()](#getWords--) | Ermittelt die Wortanzahl |
|
|  | [getLines()](#getLines--) | Ermittelt die Zeilenanzahl |
|
|  | [getTitle()](#getTitle--) | Liest Titel |
|
|  | [getAuthor()](#getAuthor--) | Ermittelt den Autor |
|
|  | [isPasswordProtected()](#isPasswordProtected--) | Ermittelt, ob das Dokument passwortgeschützt ist |
|
|  | [getTableOfContents()](#getTableOfContents--) | Inhaltsverzeichnis |
|
### WordProcessingDocumentInfo(Document wordprocessing, boolean isPasswordProtected, FileType format, long size) {#WordProcessingDocumentInfo-com.aspose.words.Document-boolean-com.groupdocs.conversion.filetypes.FileType-long-}
```
public WordProcessingDocumentInfo(Document wordprocessing, boolean isPasswordProtected, FileType format, long size)
```


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Textverarbeitung | com.aspose.words.Document |  |
| isPasswordProtected | boolean |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| Größe | long |  |

### getWords() {#getWords--}
```
public int getWords()
```


Ermittelt die Wortanzahl


**Returns:**
int - Wortanzahl

### getLines() {#getLines--}
```
public int getLines()
```


Ermittelt die Zeilenanzahl


**Returns:**
int - Zeilenanzahl

### getTitle() {#getTitle--}
```
public String getTitle()
```


Liest Titel


**Returns:**
java.lang.String - Titel

### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


Ermittelt den Autor


**Returns:**
java.lang.String - Autor

### isPasswordProtected() {#isPasswordProtected--}
```
public boolean isPasswordProtected()
```


Ermittelt, ob das Dokument passwortgeschützt ist


**Returns:**
boolean - `true` wenn das Dokument passwortgeschützt ist

### getTableOfContents() {#getTableOfContents--}
```
public List<TableOfContentsItem> getTableOfContents()
```


Inhaltsverzeichnis


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem> - Inhaltsverzeichnis

