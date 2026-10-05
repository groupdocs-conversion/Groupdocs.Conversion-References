---
title: "SpreadsheetDocumentInfo"
second_title: "GroupDocs.Conversion för Node.js via Java API-referens"
description: "Innehåller Spreadsheet-dokumentmetadata"
type: docs
weight: 39
url: /sv/nodejs-java/com.groupdocs.conversion.contracts.documentinfo/spreadsheetdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class SpreadsheetDocumentInfo extends DocumentInfo
```

Innehåller Spreadsheet-dokumentmetadata
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [SpreadsheetDocumentInfo(Workbook spreadsheet, boolean isPasswordProtected, FileType format, long size)](#SpreadsheetDocumentInfo-com.aspose.cells.Workbook-boolean-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getTitle()](#getTitle--) | Hämtar titel |
| [getWorksheetsCount()](#getWorksheetsCount--) | Hämtar antal arbetsblad |
| [getAuthor()](#getAuthor--) | Hämtar författare |
| [isPasswordProtected()](#isPasswordProtected--) | Hämtar om dokumentet är lösenordsskyddat |
| [getWorksheets()](#getWorksheets--) | Arbetsbladsnamn |
| [setWorksheets(List<String> worksheets)](#setWorksheets-java.util.List-java.lang.String--) |  |
### SpreadsheetDocumentInfo(Workbook spreadsheet, boolean isPasswordProtected, FileType format, long size) {#SpreadsheetDocumentInfo-com.aspose.cells.Workbook-boolean-com.groupdocs.conversion.filetypes.FileType-long-}
```
public SpreadsheetDocumentInfo(Workbook spreadsheet, boolean isPasswordProtected, FileType format, long size)
```


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| kalkylblad | com.aspose.cells.Workbook |  |
| isPasswordProtected | boolean |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |

### getTitle() {#getTitle--}
```
public String getTitle()
```


Hämtar titel

**Returns:**
java.lang.String - title
### getWorksheetsCount() {#getWorksheetsCount--}
```
public int getWorksheetsCount()
```


Hämtar antal arbetsblad

**Returns:**
int - antal arbetsblad
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


Hämtar om dokumentet är lösenordsskyddat

**Returns:**
boolean - true om dokumentet är lösenordsskyddat
### getWorksheets() {#getWorksheets--}
```
public List<String> getWorksheets()
```


Arbetsbladsnamn

**Returns:**
java.util.List<java.lang.String>
### setWorksheets(List<String> worksheets) {#setWorksheets-java.util.List-java.lang.String--}
```
public void setWorksheets(List<String> worksheets)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arbetsblad | java.util.List<java.lang.String> |  |

