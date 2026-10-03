---
title: "SpreadsheetDocumentInfo"
second_title: "GroupDocs.Conversion för Java API-referens"
description: "Innehåller metadata för Spreadsheet-dokument"
type: docs
weight: 36
url: /sv/java/com.groupdocs.conversion.contracts.documentinfo/spreadsheetdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class SpreadsheetDocumentInfo extends DocumentInfo
```

Innehåller metadata för Spreadsheet-dokument

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [SpreadsheetDocumentInfo(Workbook spreadsheet, boolean isPasswordProtected, FileType format, long size)](#SpreadsheetDocumentInfo-com.aspose.cells.Workbook-boolean-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getTitle()](#getTitle--) | Hämtar titel |
|
|  | [getWorksheetsCount()](#getWorksheetsCount--) | Hämtar antalet kalkylblad |
|
|  | [getAuthor()](#getAuthor--) | Hämtar författare |
|
|  | [isPasswordProtected()](#isPasswordProtected--) | Hämtar om dokumentet är lösenordsskyddat |
|
|  | [getWorksheets()](#getWorksheets--) | Kalkylbladsnamn |
|
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
| storlek | long |  |

### getTitle() {#getTitle--}
```
public String getTitle()
```


Hämtar titel


**Returns:**
java.lang.String - titel

### getWorksheetsCount() {#getWorksheetsCount--}
```
public int getWorksheetsCount()
```


Hämtar antalet kalkylblad


**Returns:**
int - antal kalkylblad

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
boolean - sant om dokumentet är lösenordsskyddat

### getWorksheets() {#getWorksheets--}
```
public List<String> getWorksheets()
```


Kalkylbladsnamn


**Returns:**
java.util.List<java.lang.String>
### setWorksheets(List<String> worksheets) {#setWorksheets-java.util.List-java.lang.String--}
```
public void setWorksheets(List<String> worksheets)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| kalkylblad | java.util.List<java.lang.String> |  |

