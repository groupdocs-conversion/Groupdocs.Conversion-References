---
title: "PdfDocumentInfo"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Berisi metadata dokumen Pdf"
type: docs
weight: 28
url: /id/java/com.groupdocs.conversion.contracts.documentinfo/pdfdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class PdfDocumentInfo extends DocumentInfo
```

Berisi metadata dokumen Pdf

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PdfDocumentInfo(Document pdf, FileType format, long size)](#PdfDocumentInfo-com.aspose.pdf.Document-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getVersion()](#getVersion--) | Mendapatkan versi |
|
|  | [getTitle()](#getTitle--) | Mendapatkan judul |
|
|  | [getAuthor()](#getAuthor--) | Mendapatkan penulis |
|
|  | [isPasswordProtected()](#isPasswordProtected--) | Mendapatkan apakah terenkripsi |
|
|  | [isLandscape()](#isLandscape--) | Mendapatkan apakah halaman berorientasi lanskap |
|
|  | [getHeight()](#getHeight--) | Mendapatkan tinggi halaman |
|
|  | [getWidth()](#getWidth--) | Mendapatkan lebar halaman |
|
|  | [getTableOfContents()](#getTableOfContents--) | Mendapatkan Daftar isi |
|
|  | [setTableOfContents(List<TableOfContentsItem> tableOfContents)](#setTableOfContents-java.util.List-com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem--) | Mengatur Daftar isi |
|
### PdfDocumentInfo(Document pdf, FileType format, long size) {#PdfDocumentInfo-com.aspose.pdf.Document-com.groupdocs.conversion.filetypes.FileType-long-}
```
public PdfDocumentInfo(Document pdf, FileType format, long size)
```


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pdf | com.aspose.pdf.Document |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |

### getVersion() {#getVersion--}
```
public String getVersion()
```


Mendapatkan versi


**Returns:**
java.lang.String - versi

### getTitle() {#getTitle--}
```
public String getTitle()
```


Mendapatkan judul


**Returns:**
java.lang.String - judul

### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


Mendapatkan penulis


**Returns:**
java.lang.String - penulis

### isPasswordProtected() {#isPasswordProtected--}
```
public boolean isPasswordProtected()
```


Mendapatkan apakah terenkripsi


**Returns:**
boolean - true jika terenkripsi

### isLandscape() {#isLandscape--}
```
public boolean isLandscape()
```


Mendapatkan apakah halaman berorientasi lanskap


**Returns:**
boolean - true jika halaman berorientasi lanskap

### getHeight() {#getHeight--}
```
public double getHeight()
```


Mendapatkan tinggi halaman


**Returns:**
double - tinggi halaman

### getWidth() {#getWidth--}
```
public double getWidth()
```


Mendapatkan lebar halaman


**Returns:**
double - lebar halaman

### getTableOfContents() {#getTableOfContents--}
```
public List<TableOfContentsItem> getTableOfContents()
```


Mendapatkan Daftar isi


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem> - Daftar isi

### setTableOfContents(List<TableOfContentsItem> tableOfContents) {#setTableOfContents-java.util.List-com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem--}
```
public void setTableOfContents(List<TableOfContentsItem> tableOfContents)
```


Mengatur Daftar isi


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | tableOfContents | java.util.List<com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem> | Daftar isi |
|

