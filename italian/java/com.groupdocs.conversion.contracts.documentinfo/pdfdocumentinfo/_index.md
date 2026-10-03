---
title: "PdfDocumentInfo"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Contiene i metadati del documento Pdf"
type: docs
weight: 28
url: /it/java/com.groupdocs.conversion.contracts.documentinfo/pdfdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class PdfDocumentInfo extends DocumentInfo
```

Contiene i metadati del documento Pdf

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PdfDocumentInfo(Document pdf, FileType format, long size)](#PdfDocumentInfo-com.aspose.pdf.Document-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getVersion()](#getVersion--) | Ottiene versione |
|
|  | [getTitle()](#getTitle--) | Ottiene il titolo |
|
|  | [getAuthor()](#getAuthor--) | Ottiene l'autore |
|
|  | [isPasswordProtected()](#isPasswordProtected--) | Ottiene se è crittografato |
|
|  | [isLandscape()](#isLandscape--) | Ottiene se la pagina è in orizzontale |
|
|  | [getHeight()](#getHeight--) | Ottiene altezza pagina |
|
|  | [getWidth()](#getWidth--) | Ottiene larghezza pagina |
|
|  | [getTableOfContents()](#getTableOfContents--) | Ottiene indice |
|
|  | [setTableOfContents(List<TableOfContentsItem> tableOfContents)](#setTableOfContents-java.util.List-com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem--) | Imposta indice |
|
### PdfDocumentInfo(Document pdf, FileType format, long size) {#PdfDocumentInfo-com.aspose.pdf.Document-com.groupdocs.conversion.filetypes.FileType-long-}
```
public PdfDocumentInfo(Document pdf, FileType format, long size)
```


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pdf | com.aspose.pdf.Document |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| dimensione | long |  |

### getVersion() {#getVersion--}
```
public String getVersion()
```


Ottiene versione


**Returns:**
java.lang.String - versione

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


Ottiene se è crittografato


**Returns:**
boolean - true se crittografato

### isLandscape() {#isLandscape--}
```
public boolean isLandscape()
```


Ottiene se la pagina è in orizzontale


**Returns:**
boolean - true se la pagina è in orizzontale

### getHeight() {#getHeight--}
```
public double getHeight()
```


Ottiene altezza pagina


**Returns:**
double - altezza pagina

### getWidth() {#getWidth--}
```
public double getWidth()
```


Ottiene larghezza pagina


**Returns:**
double - larghezza pagina

### getTableOfContents() {#getTableOfContents--}
```
public List<TableOfContentsItem> getTableOfContents()
```


Ottiene indice


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem> - indice

### setTableOfContents(List<TableOfContentsItem> tableOfContents) {#setTableOfContents-java.util.List-com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem--}
```
public void setTableOfContents(List<TableOfContentsItem> tableOfContents)
```


Imposta indice


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | tableOfContents | java.util.List<com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem> | Indice |
|

