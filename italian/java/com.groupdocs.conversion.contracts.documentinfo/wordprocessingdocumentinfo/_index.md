---
title: "WordProcessingDocumentInfo"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Contiene i metadati del documento Wordprocessing"
type: docs
weight: 45
url: /it/java/com.groupdocs.conversion.contracts.documentinfo/wordprocessingdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class WordProcessingDocumentInfo extends DocumentInfo
```

Contiene i metadati del documento Wordprocessing

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [WordProcessingDocumentInfo(Document wordprocessing, boolean isPasswordProtected, FileType format, long size)](#WordProcessingDocumentInfo-com.aspose.words.Document-boolean-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getWords()](#getWords--) | Ottiene il conteggio delle parole |
|
|  | [getLines()](#getLines--) | Ottiene il conteggio delle righe |
|
|  | [getTitle()](#getTitle--) | Ottiene il titolo |
|
|  | [getAuthor()](#getAuthor--) | Ottiene l'autore |
|
|  | [isPasswordProtected()](#isPasswordProtected--) | Ottiene se il documento è protetto da password |
|
|  | [getTableOfContents()](#getTableOfContents--) | Indice |
|
### WordProcessingDocumentInfo(Document wordprocessing, boolean isPasswordProtected, FileType format, long size) {#WordProcessingDocumentInfo-com.aspose.words.Document-boolean-com.groupdocs.conversion.filetypes.FileType-long-}
```
public WordProcessingDocumentInfo(Document wordprocessing, boolean isPasswordProtected, FileType format, long size)
```


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| elaborazione testi | com.aspose.words.Document |  |
| isPasswordProtected | booleano |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| dimensione | long |  |

### getWords() {#getWords--}
```
public int getWords()
```


Ottiene il conteggio delle parole


**Returns:**
int - conteggio delle parole

### getLines() {#getLines--}
```
public int getLines()
```


Ottiene il conteggio delle righe


**Returns:**
int - conteggio delle righe

### getTitle() {#getTitle--}
```
public String getTitle()
```


Ottiene il titolo


**Returns:**
java.lang.String - titolo

### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


Ottiene l'autore


**Returns:**
java.lang.String - autore

### isPasswordProtected() {#isPasswordProtected--}
```
public boolean isPasswordProtected()
```


Ottiene se il documento è protetto da password


**Returns:**
boolean - `true` se il documento è protetto da password

### getTableOfContents() {#getTableOfContents--}
```
public List<TableOfContentsItem> getTableOfContents()
```


Indice


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem> - indice

