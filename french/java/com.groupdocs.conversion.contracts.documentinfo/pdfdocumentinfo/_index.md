---
title: "PdfDocumentInfo"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Contient les métadonnées du document Pdf"
type: docs
weight: 28
url: /fr/java/com.groupdocs.conversion.contracts.documentinfo/pdfdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class PdfDocumentInfo extends DocumentInfo
```

Contient les métadonnées du document Pdf

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PdfDocumentInfo(Document pdf, FileType format, long size)](#PdfDocumentInfo-com.aspose.pdf.Document-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getVersion()](#getVersion--) | Obtient la version |
|
|  | [getTitle()](#getTitle--) | Obtient le titre |
|
|  | [getAuthor()](#getAuthor--) | Obtient l'auteur |
|
|  | [isPasswordProtected()](#isPasswordProtected--) | Obtient est chiffré |
|
|  | [isLandscape()](#isLandscape--) | Obtient si la page est en mode paysage |
|
|  | [getHeight()](#getHeight--) | Obtient la hauteur de la page |
|
|  | [getWidth()](#getWidth--) | Obtient la largeur de la page |
|
|  | [getTableOfContents()](#getTableOfContents--) | Obtient la table des matières |
|
|  | [setTableOfContents(List<TableOfContentsItem> tableOfContents)](#setTableOfContents-java.util.List-com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem--) | Définit la table des matières |
|
### PdfDocumentInfo(Document pdf, FileType format, long size) {#PdfDocumentInfo-com.aspose.pdf.Document-com.groupdocs.conversion.filetypes.FileType-long-}
```
public PdfDocumentInfo(Document pdf, FileType format, long size)
```


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pdf | com.aspose.pdf.Document |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |

### getVersion() {#getVersion--}
```
public String getVersion()
```


Obtient la version


**Returns:**
java.lang.String - version

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


Obtient est chiffré


**Returns:**
boolean - vrai si chiffré

### isLandscape() {#isLandscape--}
```
public boolean isLandscape()
```


Obtient si la page est en mode paysage


**Returns:**
boolean - vrai si la page est en mode paysage

### getHeight() {#getHeight--}
```
public double getHeight()
```


Obtient la hauteur de la page


**Returns:**
double - hauteur de la page

### getWidth() {#getWidth--}
```
public double getWidth()
```


Obtient la largeur de la page


**Returns:**
double - largeur de la page

### getTableOfContents() {#getTableOfContents--}
```
public List<TableOfContentsItem> getTableOfContents()
```


Obtient la table des matières


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem> - Table des matières

### setTableOfContents(List<TableOfContentsItem> tableOfContents) {#setTableOfContents-java.util.List-com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem--}
```
public void setTableOfContents(List<TableOfContentsItem> tableOfContents)
```


Définit la table des matières


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | tableOfContents | java.util.List<com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem> | Table des matières |
|

