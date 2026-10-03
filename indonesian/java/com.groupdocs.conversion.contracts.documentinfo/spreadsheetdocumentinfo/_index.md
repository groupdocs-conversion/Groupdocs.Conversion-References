---
title: "SpreadsheetDocumentInfo"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Berisi metadata dokumen Spreadsheet"
type: docs
weight: 36
url: /id/java/com.groupdocs.conversion.contracts.documentinfo/spreadsheetdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class SpreadsheetDocumentInfo extends DocumentInfo
```

Berisi metadata dokumen Spreadsheet

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [SpreadsheetDocumentInfo(Workbook spreadsheet, boolean isPasswordProtected, FileType format, long size)](#SpreadsheetDocumentInfo-com.aspose.cells.Workbook-boolean-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getTitle()](#getTitle--) | Mendapatkan judul |
|
|  | [getWorksheetsCount()](#getWorksheetsCount--) | Mendapatkan jumlah lembar kerja |
|
|  | [getAuthor()](#getAuthor--) | Mendapatkan penulis |
|
|  | [isPasswordProtected()](#isPasswordProtected--) | Mendapatkan apakah dokumen dilindungi kata sandi |
|
|  | [getWorksheets()](#getWorksheets--) | Nama lembar kerja |
|
| [setWorksheets(List<String> worksheets)](#setWorksheets-java.util.List-java.lang.String--) |  |
### SpreadsheetDocumentInfo(Workbook spreadsheet, boolean isPasswordProtected, FileType format, long size) {#SpreadsheetDocumentInfo-com.aspose.cells.Workbook-boolean-com.groupdocs.conversion.filetypes.FileType-long-}
```
public SpreadsheetDocumentInfo(Workbook spreadsheet, boolean isPasswordProtected, FileType format, long size)
```


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lembar kerja | com.aspose.cells.Workbook |  |
| isPasswordProtected | boolean |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |

### getTitle() {#getTitle--}
```
public String getTitle()
```


Mendapatkan judul


**Returns:**
java.lang.String - judul

### getWorksheetsCount() {#getWorksheetsCount--}
```
public int getWorksheetsCount()
```


Mendapatkan jumlah lembar kerja


**Returns:**
int - jumlah lembar kerja

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


Mendapatkan apakah dokumen dilindungi kata sandi


**Returns:**
boolean - true jika dokumen dilindungi kata sandi

### getWorksheets() {#getWorksheets--}
```
public List<String> getWorksheets()
```


Nama lembar kerja


**Returns:**
java.util.List<java.lang.String>
### setWorksheets(List<String> worksheets) {#setWorksheets-java.util.List-java.lang.String--}
```
public void setWorksheets(List<String> worksheets)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lembar kerja | java.util.List<java.lang.String> |  |

