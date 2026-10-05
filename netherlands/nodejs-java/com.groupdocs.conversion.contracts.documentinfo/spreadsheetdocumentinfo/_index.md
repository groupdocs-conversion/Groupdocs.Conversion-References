---
title: "SpreadsheetDocumentInfo"
second_title: "GroupDocs.Conversion for Node.js via Java API-referentie"
description: "Bevat spreadsheet-documentmetadata"
type: docs
weight: 39
url: /nl/nodejs-java/com.groupdocs.conversion.contracts.documentinfo/spreadsheetdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class SpreadsheetDocumentInfo extends DocumentInfo
```

Bevat spreadsheet-documentmetadata
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [SpreadsheetDocumentInfo(Workbook spreadsheet, boolean isPasswordProtected, FileType format, long size)](#SpreadsheetDocumentInfo-com.aspose.cells.Workbook-boolean-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getTitle()](#getTitle--) | Haalt titel op |
| [getWorksheetsCount()](#getWorksheetsCount--) | Haalt aantal werkbladen op |
| [getAuthor()](#getAuthor--) | Haalt auteur op |
| [isPasswordProtected()](#isPasswordProtected--) | Haalt op of document met wachtwoord beveiligd is |
| [getWorksheets()](#getWorksheets--) | Werkbladnamen |
| [setWorksheets(List<String> worksheets)](#setWorksheets-java.util.List-java.lang.String--) |  |
### SpreadsheetDocumentInfo(Workbook spreadsheet, boolean isPasswordProtected, FileType format, long size) {#SpreadsheetDocumentInfo-com.aspose.cells.Workbook-boolean-com.groupdocs.conversion.filetypes.FileType-long-}
```
public SpreadsheetDocumentInfo(Workbook spreadsheet, boolean isPasswordProtected, FileType format, long size)
```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| spreadsheet | com.aspose.cells.Workbook |  |
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


Haalt aantal werkbladen op

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


Haalt op of document met wachtwoord beveiligd is

**Returns:**
boolean - true als document met wachtwoord beveiligd is
### getWorksheets() {#getWorksheets--}
```
public List<String> getWorksheets()
```


Werkbladnamen

**Returns:**
java.util.List<java.lang.String>
### setWorksheets(List<String> worksheets) {#setWorksheets-java.util.List-java.lang.String--}
```
public void setWorksheets(List<String> worksheets)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| worksheets | java.util.List<java.lang.String> |  |

