---
title: "WordProcessingDocumentInfo"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Contient les métadonnées du document Wordprocessing"
type: docs
weight: 45
url: /fr/java/com.groupdocs.conversion.contracts.documentinfo/wordprocessingdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class WordProcessingDocumentInfo extends DocumentInfo
```

Contient les métadonnées du document Wordprocessing

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [WordProcessingDocumentInfo(Document wordprocessing, boolean isPasswordProtected, FileType format, long size)](#WordProcessingDocumentInfo-com.aspose.words.Document-boolean-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getWords()](#getWords--) | Obtient le nombre de mots |
|
|  | [getLines()](#getLines--) | Obtient le nombre de lignes |
|
|  | [getTitle()](#getTitle--) | Obtient le titre |
|
|  | [getAuthor()](#getAuthor--) | Obtient l'auteur |
|
|  | [isPasswordProtected()](#isPasswordProtected--) | Obtient si le document est protégé par mot de passe |
|
|  | [getTableOfContents()](#getTableOfContents--) | Table des matières |
|
### WordProcessingDocumentInfo(Document wordprocessing, boolean isPasswordProtected, FileType format, long size) {#WordProcessingDocumentInfo-com.aspose.words.Document-boolean-com.groupdocs.conversion.filetypes.FileType-long-}
```
public WordProcessingDocumentInfo(Document wordprocessing, boolean isPasswordProtected, FileType format, long size)
```


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| wordprocessing | com.aspose.words.Document |  |
| isPasswordProtected | booléen |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |

### getWords() {#getWords--}
```
public int getWords()
```


Obtient le nombre de mots


**Returns:**
int - nombre de mots

### getLines() {#getLines--}
```
public int getLines()
```


Obtient le nombre de lignes


**Returns:**
int - nombre de lignes

### getTitle() {#getTitle--}
```
public String getTitle()
```


Obtient le titre


**Returns:**
java.lang.String - titre

### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


Obtient l'auteur


**Returns:**
java.lang.String - auteur

### isPasswordProtected() {#isPasswordProtected--}
```
public boolean isPasswordProtected()
```


Obtient si le document est protégé par mot de passe


**Returns:**
boolean - `true` si le document est protégé par mot de passe

### getTableOfContents() {#getTableOfContents--}
```
public List<TableOfContentsItem> getTableOfContents()
```


Table des matières


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem> - Table des matières

