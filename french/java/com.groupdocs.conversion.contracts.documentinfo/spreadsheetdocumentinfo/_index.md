---
title: "SpreadsheetDocumentInfo"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Contient les métadonnées du document Spreadsheet"
type: docs
weight: 36
url: /fr/java/com.groupdocs.conversion.contracts.documentinfo/spreadsheetdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class SpreadsheetDocumentInfo extends DocumentInfo
```

Contient les métadonnées du document Spreadsheet

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [SpreadsheetDocumentInfo(Workbook spreadsheet, boolean isPasswordProtected, FileType format, long size)](#SpreadsheetDocumentInfo-com.aspose.cells.Workbook-boolean-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getTitle()](#getTitle--) | Obtient le titre |
|
|  | [getWorksheetsCount()](#getWorksheetsCount--) | Obtient le nombre de feuilles de calcul |
|
|  | [getAuthor()](#getAuthor--) | Obtient l'auteur |
|
|  | [isPasswordProtected()](#isPasswordProtected--) | Obtient si le document est protégé par mot de passe |
|
|  | [getWorksheets()](#getWorksheets--) | Noms des feuilles de calcul |
|
| [setWorksheets(List<String> worksheets)](#setWorksheets-java.util.List-java.lang.String--) |  |
### SpreadsheetDocumentInfo(Workbook spreadsheet, boolean isPasswordProtected, FileType format, long size) {#SpreadsheetDocumentInfo-com.aspose.cells.Workbook-boolean-com.groupdocs.conversion.filetypes.FileType-long-}
```
public SpreadsheetDocumentInfo(Workbook spreadsheet, boolean isPasswordProtected, FileType format, long size)
```


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| feuille de calcul | com.aspose.cells.Workbook |  |
| isPasswordProtected | booléen |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |

### getTitle() {#getTitle--}
```
public String getTitle()
```


Obtient le titre


**Returns:**
java.lang.String - titre

### getWorksheetsCount() {#getWorksheetsCount--}
```
public int getWorksheetsCount()
```


Obtient le nombre de feuilles de calcul


**Returns:**
int - nombre de feuilles de calcul

### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


Obtient l'auteur


**Returns:**
java.lang.String - auteur

### isPasswordProtected() {#isPasswordProtected--}
```
public boolean isPasswordProtected()
```


Obtient si le document est protégé par mot de passe


**Returns:**
booléen - vrai si le document est protégé par mot de passe

### getWorksheets() {#getWorksheets--}
```
public List<String> getWorksheets()
```


Noms des feuilles de calcul


**Returns:**
java.util.List<java.lang.String>
### setWorksheets(List<String> worksheets) {#setWorksheets-java.util.List-java.lang.String--}
```
public void setWorksheets(List<String> worksheets)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| feuilles de calcul | java.util.List<java.lang.String> |  |

