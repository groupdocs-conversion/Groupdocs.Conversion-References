---
title: PdfDocumentInfo
second_title: GroupDocs.Conversion for Node.js via Java API Reference
description: Contains Pdf document metadata
type: docs
weight: 31
url: /nodejs-java/com.groupdocs.conversion.contracts.documentinfo/pdfdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class PdfDocumentInfo extends DocumentInfo
```

Contains Pdf document metadata
## Constructors

| Constructor | Description |
| --- | --- |
| [PdfDocumentInfo(Document pdf, FileType format, long size)](#PdfDocumentInfo-com.aspose.pdf.Document-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Methods

| Method | Description |
| --- | --- |
| [getVersion()](#getVersion--) | Gets version |
| [getTitle()](#getTitle--) | Gets title |
| [getAuthor()](#getAuthor--) | Gets author |
| [isPasswordProtected()](#isPasswordProtected--) | Gets is encrypted |
| [isLandscape()](#isLandscape--) | Gets is page landscaped |
| [getHeight()](#getHeight--) | Gets page height |
| [getWidth()](#getWidth--) | Gets page width |
| [getTableOfContents()](#getTableOfContents--) | Gets Table of contents |
| [setTableOfContents(List<TableOfContentsItem> tableOfContents)](#setTableOfContents-java.util.List-com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem--) | Sets Table of contents |
### PdfDocumentInfo(Document pdf, FileType format, long size) {#PdfDocumentInfo-com.aspose.pdf.Document-com.groupdocs.conversion.filetypes.FileType-long-}
```
public PdfDocumentInfo(Document pdf, FileType format, long size)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pdf | com.aspose.pdf.Document |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |

### getVersion() {#getVersion--}
```
public String getVersion()
```


Gets version

**Returns:**
java.lang.String - version
### getTitle() {#getTitle--}
```
public String getTitle()
```


Gets title

**Returns:**
java.lang.String - title
### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


Gets author

**Returns:**
java.lang.String - author
### isPasswordProtected() {#isPasswordProtected--}
```
public boolean isPasswordProtected()
```


Gets is encrypted

**Returns:**
boolean - true if encrypted
### isLandscape() {#isLandscape--}
```
public boolean isLandscape()
```


Gets is page landscaped

**Returns:**
boolean - true if page is landscaped
### getHeight() {#getHeight--}
```
public double getHeight()
```


Gets page height

**Returns:**
double - page height
### getWidth() {#getWidth--}
```
public double getWidth()
```


Gets page width

**Returns:**
double - page width
### getTableOfContents() {#getTableOfContents--}
```
public List<TableOfContentsItem> getTableOfContents()
```


Gets Table of contents

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem> - Table of contents
### setTableOfContents(List<TableOfContentsItem> tableOfContents) {#setTableOfContents-java.util.List-com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem--}
```
public void setTableOfContents(List<TableOfContentsItem> tableOfContents)
```


Sets Table of contents

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tableOfContents | java.util.List<com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem> | Table of contents |

