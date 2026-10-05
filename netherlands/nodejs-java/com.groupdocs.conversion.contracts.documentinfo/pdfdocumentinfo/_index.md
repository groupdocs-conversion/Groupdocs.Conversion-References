---
title: "PdfDocumentInfo"
second_title: "GroupDocs.Conversion for Node.js via Java API-referentie"
description: "Bevat Pdf-documentmetadata"
type: docs
weight: 31
url: /nl/nodejs-java/com.groupdocs.conversion.contracts.documentinfo/pdfdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class PdfDocumentInfo extends DocumentInfo
```

Bevat Pdf-documentmetadata
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [PdfDocumentInfo(Document pdf, FileType format, long size)](#PdfDocumentInfo-com.aspose.pdf.Document-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getVersion()](#getVersion--) | Haalt versie op |
| [getTitle()](#getTitle--) | Haalt titel op |
| [getAuthor()](#getAuthor--) | Haalt auteur op |
| [isPasswordProtected()](#isPasswordProtected--) | Haalt op of versleuteld is |
| [isLandscape()](#isLandscape--) | Haalt op of pagina liggend is |
| [getHeight()](#getHeight--) | Haalt paginahoogte op |
| [getWidth()](#getWidth--) | Haalt paginabreedte op |
| [getTableOfContents()](#getTableOfContents--) | Haalt inhoudsopgave op |
| [setTableOfContents(List<TableOfContentsItem> tableOfContents)](#setTableOfContents-java.util.List-com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem--) | Stelt inhoudsopgave in |
### PdfDocumentInfo(Document pdf, FileType format, long size) {#PdfDocumentInfo-com.aspose.pdf.Document-com.groupdocs.conversion.filetypes.FileType-long-}
```
public PdfDocumentInfo(Document pdf, FileType format, long size)
```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pdf | com.aspose.pdf.Document |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |

### getVersion() {#getVersion--}
```
public String getVersion()
```


Haalt versie op

**Returns:**
java.lang.String - versie
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


Haalt op of versleuteld is

**Returns:**
boolean - true als versleuteld
### isLandscape() {#isLandscape--}
```
public boolean isLandscape()
```


Haalt op of pagina liggend is

**Returns:**
boolean - true als pagina liggend is
### getHeight() {#getHeight--}
```
public double getHeight()
```


Haalt paginahoogte op

**Returns:**
double - paginahoogte
### getWidth() {#getWidth--}
```
public double getWidth()
```


Haalt paginabreedte op

**Returns:**
double - paginabreedte
### getTableOfContents() {#getTableOfContents--}
```
public List<TableOfContentsItem> getTableOfContents()
```


Haalt inhoudsopgave op

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem> - inhoudsopgave
### setTableOfContents(List<TableOfContentsItem> tableOfContents) {#setTableOfContents-java.util.List-com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem--}
```
public void setTableOfContents(List<TableOfContentsItem> tableOfContents)
```


Stelt inhoudsopgave in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| tableOfContents | java.util.List<com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem> | Inhoudsopgave |

