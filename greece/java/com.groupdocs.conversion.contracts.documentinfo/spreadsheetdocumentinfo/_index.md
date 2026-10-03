---
title: "SpreadsheetDocumentInfo"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Περιέχει μεταδεδομένα εγγράφου λογιστικού φύλλου"
type: docs
weight: 36
url: /el/java/com.groupdocs.conversion.contracts.documentinfo/spreadsheetdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class SpreadsheetDocumentInfo extends DocumentInfo
```

Περιέχει μεταδεδομένα εγγράφου λογιστικού φύλλου

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [SpreadsheetDocumentInfo(Workbook spreadsheet, boolean isPasswordProtected, FileType format, long size)](#SpreadsheetDocumentInfo-com.aspose.cells.Workbook-boolean-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getTitle()](#getTitle--) | Λαμβάνει τίτλο |
|
|  | [getWorksheetsCount()](#getWorksheetsCount--) | Λαμβάνει τον αριθμό των φύλλων εργασίας |
|
|  | [getAuthor()](#getAuthor--) | Λαμβάνει συγγραφέα |
|
|  | [isPasswordProtected()](#isPasswordProtected--) | Λαμβάνει εάν το έγγραφο είναι προστατευμένο με κωδικό |
|
|  | [getWorksheets()](#getWorksheets--) | Ονόματα φύλλων εργασίας |
|
| [setWorksheets(List<String> worksheets)](#setWorksheets-java.util.List-java.lang.String--) |  |
### SpreadsheetDocumentInfo(Workbook spreadsheet, boolean isPasswordProtected, FileType format, long size) {#SpreadsheetDocumentInfo-com.aspose.cells.Workbook-boolean-com.groupdocs.conversion.filetypes.FileType-long-}
```
public SpreadsheetDocumentInfo(Workbook spreadsheet, boolean isPasswordProtected, FileType format, long size)
```


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| Φύλλο εργασίας | com.aspose.cells.Workbook |  |
| isPasswordProtected | boolean |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| μέγεθος | long |  |

### getTitle() {#getTitle--}
```
public String getTitle()
```


Λαμβάνει τίτλο


**Returns:**
java.lang.String - τίτλος

### getWorksheetsCount() {#getWorksheetsCount--}
```
public int getWorksheetsCount()
```


Λαμβάνει τον αριθμό των φύλλων εργασίας


**Returns:**
int - αριθμός φύλλων εργασίας

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


Λαμβάνει εάν το έγγραφο είναι προστατευμένο με κωδικό


**Returns:**
boolean - true εάν το έγγραφο είναι προστατευμένο με κωδικό

### getWorksheets() {#getWorksheets--}
```
public List<String> getWorksheets()
```


Ονόματα φύλλων εργασίας


**Returns:**
java.util.List<java.lang.String>
### setWorksheets(List<String> worksheets) {#setWorksheets-java.util.List-java.lang.String--}
```
public void setWorksheets(List<String> worksheets)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| φύλλα εργασίας | java.util.List<java.lang.String> |  |

