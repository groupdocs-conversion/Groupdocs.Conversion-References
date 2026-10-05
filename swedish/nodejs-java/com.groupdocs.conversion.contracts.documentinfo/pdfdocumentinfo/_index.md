---
title: "PdfDocumentInfo"
second_title: "GroupDocs.Conversion för Node.js via Java API-referens"
description: "Innehåller Pdf-dokumentmetadata"
type: docs
weight: 31
url: /sv/nodejs-java/com.groupdocs.conversion.contracts.documentinfo/pdfdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class PdfDocumentInfo extends DocumentInfo
```

Innehåller Pdf-dokumentmetadata
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [PdfDocumentInfo(Document pdf, FileType format, long size)](#PdfDocumentInfo-com.aspose.pdf.Document-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getVersion()](#getVersion--) | Hämtar version |
| [getTitle()](#getTitle--) | Hämtar titel |
| [getAuthor()](#getAuthor--) | Hämtar författare |
| [isPasswordProtected()](#isPasswordProtected--) | Hämtar om krypterad |
| [isLandscape()](#isLandscape--) | Hämtar om sidan är liggande |
| [getHeight()](#getHeight--) | Hämtar sidans höjd |
| [getWidth()](#getWidth--) | Hämtar sidans bredd |
| [getTableOfContents()](#getTableOfContents--) | Hämtar innehållsförteckning |
| [setTableOfContents(List<TableOfContentsItem> tableOfContents)](#setTableOfContents-java.util.List-com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem--) | Sätter innehållsförteckning |
### PdfDocumentInfo(Document pdf, FileType format, long size) {#PdfDocumentInfo-com.aspose.pdf.Document-com.groupdocs.conversion.filetypes.FileType-long-}
```
public PdfDocumentInfo(Document pdf, FileType format, long size)
```


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pdf | com.aspose.pdf.Document |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |

### getVersion() {#getVersion--}
```
public String getVersion()
```


Hämtar version

**Returns:**
java.lang.String - version
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


Hämtar om krypterad

**Returns:**
boolean - true om krypterad
### isLandscape() {#isLandscape--}
```
public boolean isLandscape()
```


Hämtar om sidan är liggande

**Returns:**
boolean - true om sidan är liggande
### getHeight() {#getHeight--}
```
public double getHeight()
```


Hämtar sidans höjd

**Returns:**
double - sidans höjd
### getWidth() {#getWidth--}
```
public double getWidth()
```


Hämtar sidans bredd

**Returns:**
double - sidans bredd
### getTableOfContents() {#getTableOfContents--}
```
public List<TableOfContentsItem> getTableOfContents()
```


Hämtar innehållsförteckning

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem> - Innehållsförteckning
### setTableOfContents(List<TableOfContentsItem> tableOfContents) {#setTableOfContents-java.util.List-com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem--}
```
public void setTableOfContents(List<TableOfContentsItem> tableOfContents)
```


Sätter innehållsförteckning

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tableOfContents | java.util.List<com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem> | Innehållsförteckning |

