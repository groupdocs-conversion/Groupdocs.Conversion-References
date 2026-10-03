---
title: "SpreadsheetDocumentInfo"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Enthält Metadaten des Tabellenkalkulationsdokuments"
type: docs
weight: 36
url: /de/java/com.groupdocs.conversion.contracts.documentinfo/spreadsheetdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class SpreadsheetDocumentInfo extends DocumentInfo
```

Enthält Metadaten des Tabellenkalkulationsdokuments

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [SpreadsheetDocumentInfo(Workbook spreadsheet, boolean isPasswordProtected, FileType format, long size)](#SpreadsheetDocumentInfo-com.aspose.cells.Workbook-boolean-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getTitle()](#getTitle--) | Liest Titel |
|
|  | [getWorksheetsCount()](#getWorksheetsCount--) | Ermittelt die Anzahl der Arbeitsblätter |
|
|  | [getAuthor()](#getAuthor--) | Ermittelt den Autor |
|
|  | [isPasswordProtected()](#isPasswordProtected--) | Ermittelt, ob das Dokument passwortgeschützt ist |
|
|  | [getWorksheets()](#getWorksheets--) | Namen der Arbeitsblätter |
|
| [setWorksheets(List<String> worksheets)](#setWorksheets-java.util.List-java.lang.String--) |  |
### SpreadsheetDocumentInfo(Workbook spreadsheet, boolean isPasswordProtected, FileType format, long size) {#SpreadsheetDocumentInfo-com.aspose.cells.Workbook-boolean-com.groupdocs.conversion.filetypes.FileType-long-}
```
public SpreadsheetDocumentInfo(Workbook spreadsheet, boolean isPasswordProtected, FileType format, long size)
```


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Tabellenkalkulation | com.aspose.cells.Workbook |  |
| isPasswordProtected | boolean |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| Größe | long |  |

### getTitle() {#getTitle--}
```
public String getTitle()
```


Liest Titel


**Returns:**
java.lang.String - Titel

### getWorksheetsCount() {#getWorksheetsCount--}
```
public int getWorksheetsCount()
```


Ermittelt die Anzahl der Arbeitsblätter


**Returns:**
int - Anzahl der Arbeitsblätter

### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


Ermittelt den Autor


**Returns:**
java.lang.String - Autor

### isPasswordProtected() {#isPasswordProtected--}
```
public boolean isPasswordProtected()
```


Ermittelt, ob das Dokument passwortgeschützt ist


**Returns:**
boolean - true, wenn das Dokument passwortgeschützt ist

### getWorksheets() {#getWorksheets--}
```
public List<String> getWorksheets()
```


Namen der Arbeitsblätter


**Returns:**
java.util.List<java.lang.String>
### setWorksheets(List<String> worksheets) {#setWorksheets-java.util.List-java.lang.String--}
```
public void setWorksheets(List<String> worksheets)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Arbeitsblätter | java.util.List<java.lang.String> |  |

