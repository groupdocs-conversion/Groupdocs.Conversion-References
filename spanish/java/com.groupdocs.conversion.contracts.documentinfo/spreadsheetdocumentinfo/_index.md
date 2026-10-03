---
title: "SpreadsheetDocumentInfo"
second_title: "Referencia de API de GroupDocs.Conversion for Java"
description: "Contiene metadatos del documento de hoja de cálculo"
type: docs
weight: 36
url: /es/java/com.groupdocs.conversion.contracts.documentinfo/spreadsheetdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class SpreadsheetDocumentInfo extends DocumentInfo
```

Contiene metadatos del documento de hoja de cálculo

## Constructores

| Constructor | Descripción |
| --- | --- |
| [SpreadsheetDocumentInfo(Workbook spreadsheet, boolean isPasswordProtected, FileType format, long size)](#SpreadsheetDocumentInfo-com.aspose.cells.Workbook-boolean-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getTitle()](#getTitle--) | Obtiene el título |
|
|  | [getWorksheetsCount()](#getWorksheetsCount--) | Obtiene la cantidad de hojas de cálculo |
|
|  | [getAuthor()](#getAuthor--) | Obtiene el autor |
|
|  | [isPasswordProtected()](#isPasswordProtected--) | Obtiene si el documento está protegido con contraseña |
|
|  | [getWorksheets()](#getWorksheets--) | Nombres de hojas de cálculo |
|
| [setWorksheets(List<String> worksheets)](#setWorksheets-java.util.List-java.lang.String--) |  |
### SpreadsheetDocumentInfo(Workbook spreadsheet, boolean isPasswordProtected, FileType format, long size) {#SpreadsheetDocumentInfo-com.aspose.cells.Workbook-boolean-com.groupdocs.conversion.filetypes.FileType-long-}
```
public SpreadsheetDocumentInfo(Workbook spreadsheet, boolean isPasswordProtected, FileType format, long size)
```


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| hoja de cálculo | com.aspose.cells.Workbook |  |
| isPasswordProtected | booleano |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |

### getTitle() {#getTitle--}
```
public String getTitle()
```


Obtiene el título


**Returns:**
java.lang.String - title

### getWorksheetsCount() {#getWorksheetsCount--}
```
public int getWorksheetsCount()
```


Obtiene la cantidad de hojas de cálculo


**Returns:**
int - recuento de hojas de cálculo

### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


Obtiene el autor


**Returns:**
java.lang.String - autor

### isPasswordProtected() {#isPasswordProtected--}
```
public boolean isPasswordProtected()
```


Obtiene si el documento está protegido con contraseña


**Returns:**
boolean - verdadero si el documento está protegido con contraseña

### getWorksheets() {#getWorksheets--}
```
public List<String> getWorksheets()
```


Nombres de hojas de cálculo


**Returns:**
java.util.List<java.lang.String>
### setWorksheets(List<String> worksheets) {#setWorksheets-java.util.List-java.lang.String--}
```
public void setWorksheets(List<String> worksheets)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| hojas de cálculo | java.util.List<java.lang.String> |  |

