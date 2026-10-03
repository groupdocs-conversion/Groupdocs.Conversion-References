---
title: "SpreadsheetDocumentInfo"
second_title: "GroupDocs.Conversion voor Java API-referentie"
description: "Bevat metadata van Spreadsheet-document"
type: docs
weight: 36
url: /nl/java/com.groupdocs.conversion.contracts.documentinfo/spreadsheetdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class SpreadsheetDocumentInfo extends DocumentInfo
```

Bevat metadata van Spreadsheet-document

## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [SpreadsheetDocumentInfo(Workbook spreadsheet, boolean isPasswordProtected, FileType format, long size)](#SpreadsheetDocumentInfo-com.aspose.cells.Workbook-boolean-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getTitle()](#getTitle--) | Haalt titel op |
|
|  | [getWorksheetsCount()](#getWorksheetsCount--) | Haalt het aantal werkbladen op |
|
|  | [getAuthor()](#getAuthor--) | Haalt auteur op |
|
|  | [isPasswordProtected()](#isPasswordProtected--) | Haalt op of het document met wachtwoord is beveiligd |
|
|  | [getWorksheets()](#getWorksheets--) | Namen van werkbladen |
|
| [setWorksheets(List<String> worksheets)](#setWorksheets-java.util.List-java.lang.String--) |  |
### SpreadsheetDocumentInfo(Workbook spreadsheet, boolean isPasswordProtected, FileType format, long size) {#SpreadsheetDocumentInfo-com.aspose.cells.Workbook-boolean-com.groupdocs.conversion.filetypes.FileType-long-}
```
public SpreadsheetDocumentInfo(Workbook spreadsheet, boolean isPasswordProtected, FileType format, long size)
```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| werkblad | com.aspose.cells.Workbook |  |
| isPasswordProtected | boolean |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |

### getTitle() {#getTitle--}
```
public String getTitle()
```


Haalt titel op


**Returns:**
java.lang.String - titel

### getWorksheetsCount() {#getWorksheetsCount--}
```
public int getWorksheetsCount()
```


Haalt het aantal werkbladen op


**Returns:**
int - aantal werkbladen

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


Haalt op of het document met wachtwoord is beveiligd


**Returns:**
boolean - true als het document met wachtwoord is beveiligd

### getWorksheets() {#getWorksheets--}
```
public List<String> getWorksheets()
```


Namen van werkbladen


**Returns:**
java.util.List<java.lang.String>
### setWorksheets(List<String> worksheets) {#setWorksheets-java.util.List-java.lang.String--}
```
public void setWorksheets(List<String> worksheets)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| werkbladen | java.util.List<java.lang.String> |  |

