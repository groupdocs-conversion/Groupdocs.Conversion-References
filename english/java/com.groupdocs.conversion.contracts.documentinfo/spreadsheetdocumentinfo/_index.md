---
title: SpreadsheetDocumentInfo
second_title: GroupDocs.Conversion for Java API Reference
description: Contains Spreadsheet document metadata
type: docs
weight: 36
url: /java/com.groupdocs.conversion.contracts.documentinfo/spreadsheetdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class SpreadsheetDocumentInfo extends DocumentInfo
```

Contains Spreadsheet document metadata
## Constructors

| Constructor | Description |
| --- | --- |
| [SpreadsheetDocumentInfo(Workbook spreadsheet, boolean isPasswordProtected, FileType format, long size)](#SpreadsheetDocumentInfo-com.aspose.cells.Workbook-boolean-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Methods

| Method | Description |
| --- | --- |
| [getTitle()](#getTitle--) | Gets title |
| [getWorksheetsCount()](#getWorksheetsCount--) | Gets worksheets count |
| [getAuthor()](#getAuthor--) | Gets author |
| [isPasswordProtected()](#isPasswordProtected--) | Gets is document password protected |
| [getWorksheets()](#getWorksheets--) | Worksheets names |
| [setWorksheets(List<String> worksheets)](#setWorksheets-java.util.List-java.lang.String--) |  |
### SpreadsheetDocumentInfo(Workbook spreadsheet, boolean isPasswordProtected, FileType format, long size) {#SpreadsheetDocumentInfo-com.aspose.cells.Workbook-boolean-com.groupdocs.conversion.filetypes.FileType-long-}
```
public SpreadsheetDocumentInfo(Workbook spreadsheet, boolean isPasswordProtected, FileType format, long size)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| spreadsheet | com.aspose.cells.Workbook |  |
| isPasswordProtected | boolean |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |

### getTitle() {#getTitle--}
```
public String getTitle()
```


Gets title

**Returns:**
java.lang.String - title
### getWorksheetsCount() {#getWorksheetsCount--}
```
public int getWorksheetsCount()
```


Gets worksheets count

**Returns:**
int - worksheets count
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


Gets is document password protected

**Returns:**
boolean - true if document is password protected
### getWorksheets() {#getWorksheets--}
```
public List<String> getWorksheets()
```


Worksheets names

**Returns:**
java.util.List<java.lang.String>
### setWorksheets(List<String> worksheets) {#setWorksheets-java.util.List-java.lang.String--}
```
public void setWorksheets(List<String> worksheets)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| worksheets | java.util.List<java.lang.String> |  |

