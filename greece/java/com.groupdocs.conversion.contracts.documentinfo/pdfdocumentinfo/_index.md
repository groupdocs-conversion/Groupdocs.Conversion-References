---
title: "PdfDocumentInfo"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Περιέχει μεταδεδομένα εγγράφου PDF"
type: docs
weight: 28
url: /el/java/com.groupdocs.conversion.contracts.documentinfo/pdfdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class PdfDocumentInfo extends DocumentInfo
```

Περιέχει μεταδεδομένα εγγράφου PDF

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [PdfDocumentInfo(Document pdf, FileType format, long size)](#PdfDocumentInfo-com.aspose.pdf.Document-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getVersion()](#getVersion--) | Λαμβάνει έκδοση |
|
|  | [getTitle()](#getTitle--) | Λαμβάνει τίτλο |
|
|  | [getAuthor()](#getAuthor--) | Λαμβάνει συγγραφέα |
|
|  | [isPasswordProtected()](#isPasswordProtected--) | Λαμβάνει αν είναι κρυπτογραφημένο |
|
|  | [isLandscape()](#isLandscape--) | Λαμβάνει αν η σελίδα είναι οριζόντια |
|
|  | [getHeight()](#getHeight--) | Λαμβάνει ύψος σελίδας |
|
|  | [getWidth()](#getWidth--) | Λαμβάνει πλάτος σελίδας |
|
|  | [getTableOfContents()](#getTableOfContents--) | Λαμβάνει πίνακα περιεχομένων |
|
|  | [setTableOfContents(List<TableOfContentsItem> tableOfContents)](#setTableOfContents-java.util.List-com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem--) | Ορίζει πίνακα περιεχομένων |
|
### PdfDocumentInfo(Document pdf, FileType format, long size) {#PdfDocumentInfo-com.aspose.pdf.Document-com.groupdocs.conversion.filetypes.FileType-long-}
```
public PdfDocumentInfo(Document pdf, FileType format, long size)
```


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| pdf | com.aspose.pdf.Document |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| μέγεθος | long |  |

### getVersion() {#getVersion--}
```
public String getVersion()
```


Λαμβάνει έκδοση


**Returns:**
java.lang.String - έκδοση

### getTitle() {#getTitle--}
```
public String getTitle()
```


Λαμβάνει τίτλο


**Returns:**
java.lang.String - τίτλος

### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


Λαμβάνει συγγραφέα


**Returns:**
java.lang.String - συγγραφέας

### isPasswordProtected() {#isPasswordProtected--}
```
public boolean isPasswordProtected()
```


Λαμβάνει αν είναι κρυπτογραφημένο


**Returns:**
boolean - true αν είναι κρυπτογραφημένο

### isLandscape() {#isLandscape--}
```
public boolean isLandscape()
```


Λαμβάνει αν η σελίδα είναι οριζόντια


**Returns:**
boolean - true αν η σελίδα είναι οριζόντια

### getHeight() {#getHeight--}
```
public double getHeight()
```


Λαμβάνει ύψος σελίδας


**Returns:**
double - ύψος σελίδας

### getWidth() {#getWidth--}
```
public double getWidth()
```


Λαμβάνει πλάτος σελίδας


**Returns:**
double - πλάτος σελίδας

### getTableOfContents() {#getTableOfContents--}
```
public List<TableOfContentsItem> getTableOfContents()
```


Λαμβάνει πίνακα περιεχομένων


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem> - Πίνακας περιεχομένων

### setTableOfContents(List<TableOfContentsItem> tableOfContents) {#setTableOfContents-java.util.List-com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem--}
```
public void setTableOfContents(List<TableOfContentsItem> tableOfContents)
```


Ορίζει πίνακα περιεχομένων


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | tableOfContents | java.util.List<com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem> | Πίνακας περιεχομένων |
|

