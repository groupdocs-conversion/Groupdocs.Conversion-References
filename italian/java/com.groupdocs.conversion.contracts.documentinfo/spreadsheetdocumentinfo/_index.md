---
title: "SpreadsheetDocumentInfo"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Contiene i metadati del documento Spreadsheet"
type: docs
weight: 36
url: /it/java/com.groupdocs.conversion.contracts.documentinfo/spreadsheetdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class SpreadsheetDocumentInfo extends DocumentInfo
```

Contiene i metadati del documento Spreadsheet

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [SpreadsheetDocumentInfo(Workbook spreadsheet, boolean isPasswordProtected, FileType format, long size)](#SpreadsheetDocumentInfo-com.aspose.cells.Workbook-boolean-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getTitle()](#getTitle--) | Ottiene il titolo |
|
|  | [getWorksheetsCount()](#getWorksheetsCount--) | Ottiene il conteggio dei fogli di lavoro |
|
|  | [getAuthor()](#getAuthor--) | Ottiene l'autore |
|
|  | [isPasswordProtected()](#isPasswordProtected--) | Ottiene se il documento è protetto da password |
|
|  | [getWorksheets()](#getWorksheets--) | Nomi dei fogli di lavoro |
|
| [setWorksheets(List<String> worksheets)](#setWorksheets-java.util.List-java.lang.String--) |  |
### SpreadsheetDocumentInfo(Workbook spreadsheet, boolean isPasswordProtected, FileType format, long size) {#SpreadsheetDocumentInfo-com.aspose.cells.Workbook-boolean-com.groupdocs.conversion.filetypes.FileType-long-}
```
public SpreadsheetDocumentInfo(Workbook spreadsheet, boolean isPasswordProtected, FileType format, long size)
```


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| foglio di calcolo | com.aspose.cells.Workbook |  |
| isPasswordProtected | booleano |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| dimensione | long |  |

### getTitle() {#getTitle--}
```
public String getTitle()
```


Ottiene il titolo


**Returns:**
java.lang.String - titolo

### getWorksheetsCount() {#getWorksheetsCount--}
```
public int getWorksheetsCount()
```


Ottiene il conteggio dei fogli di lavoro


**Returns:**
int - conteggio dei fogli di lavoro

### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


Ottiene l'autore


**Returns:**
java.lang.String - autore

### isPasswordProtected() {#isPasswordProtected--}
```
public boolean isPasswordProtected()
```


Ottiene se il documento è protetto da password


**Returns:**
boolean - true se il documento è protetto da password

### getWorksheets() {#getWorksheets--}
```
public List<String> getWorksheets()
```


Nomi dei fogli di lavoro


**Returns:**
java.util.List<java.lang.String>
### setWorksheets(List<String> worksheets) {#setWorksheets-java.util.List-java.lang.String--}
```
public void setWorksheets(List<String> worksheets)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fogli di lavoro | java.util.List<java.lang.String> |  |

