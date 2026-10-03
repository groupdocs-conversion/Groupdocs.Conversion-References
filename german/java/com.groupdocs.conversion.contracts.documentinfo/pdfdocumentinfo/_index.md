---
title: "PdfDocumentInfo"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Enthält Metadaten für PDF-Dokumente"
type: docs
weight: 28
url: /de/java/com.groupdocs.conversion.contracts.documentinfo/pdfdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class PdfDocumentInfo extends DocumentInfo
```

Enthält Metadaten für PDF-Dokumente

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PdfDocumentInfo(Document pdf, FileType format, long size)](#PdfDocumentInfo-com.aspose.pdf.Document-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getVersion()](#getVersion--) | Liefert Version |
|
|  | [getTitle()](#getTitle--) | Liest Titel |
|
|  | [getAuthor()](#getAuthor--) | Ermittelt den Autor |
|
|  | [isPasswordProtected()](#isPasswordProtected--) | Liefert, ob verschlüsselt ist |
|
|  | [isLandscape()](#isLandscape--) | Liefert, ob Seite im Querformat ist |
|
|  | [getHeight()](#getHeight--) | Liefert Seitenhöhe |
|
|  | [getWidth()](#getWidth--) | Liefert Seitenbreite |
|
|  | [getTableOfContents()](#getTableOfContents--) | Liefert Inhaltsverzeichnis |
|
|  | [setTableOfContents(List<TableOfContentsItem> tableOfContents)](#setTableOfContents-java.util.List-com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem--) | Setzt Inhaltsverzeichnis |
|
### PdfDocumentInfo(Document pdf, FileType format, long size) {#PdfDocumentInfo-com.aspose.pdf.Document-com.groupdocs.conversion.filetypes.FileType-long-}
```
public PdfDocumentInfo(Document pdf, FileType format, long size)
```


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pdf | com.aspose.pdf.Document |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| Größe | long |  |

### getVersion() {#getVersion--}
```
public String getVersion()
```


Liefert Version


**Returns:**
java.lang.String - Version

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


Liefert, ob verschlüsselt ist


**Returns:**
boolean - true, wenn verschlüsselt

### isLandscape() {#isLandscape--}
```
public boolean isLandscape()
```


Liefert, ob Seite im Querformat ist


**Returns:**
boolean - true, wenn die Seite im Querformat ist

### getHeight() {#getHeight--}
```
public double getHeight()
```


Liefert Seitenhöhe


**Returns:**
double - Seitenhöhe

### getWidth() {#getWidth--}
```
public double getWidth()
```


Liefert Seitenbreite


**Returns:**
double - Seitenbreite

### getTableOfContents() {#getTableOfContents--}
```
public List<TableOfContentsItem> getTableOfContents()
```


Liefert Inhaltsverzeichnis


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem> - Inhaltsverzeichnis

### setTableOfContents(List<TableOfContentsItem> tableOfContents) {#setTableOfContents-java.util.List-com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem--}
```
public void setTableOfContents(List<TableOfContentsItem> tableOfContents)
```


Setzt Inhaltsverzeichnis


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | tableOfContents | java.util.List<com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem> | Inhaltsverzeichnis |
|

