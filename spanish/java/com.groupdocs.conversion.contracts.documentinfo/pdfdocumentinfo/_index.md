---
title: "PdfDocumentInfo"
second_title: "Referencia de API de GroupDocs.Conversion for Java"
description: "Contiene metadatos del documento de Pdf"
type: docs
weight: 28
url: /es/java/com.groupdocs.conversion.contracts.documentinfo/pdfdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class PdfDocumentInfo extends DocumentInfo
```

Contiene metadatos del documento de Pdf

## Constructores

| Constructor | Descripción |
| --- | --- |
| [PdfDocumentInfo(Document pdf, FileType format, long size)](#PdfDocumentInfo-com.aspose.pdf.Document-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getVersion()](#getVersion--) | Obtiene la versión |
|
|  | [getTitle()](#getTitle--) | Obtiene el título |
|
|  | [getAuthor()](#getAuthor--) | Obtiene el autor |
|
|  | [isPasswordProtected()](#isPasswordProtected--) | Obtiene si está encriptado |
|
|  | [isLandscape()](#isLandscape--) | Obtiene si la página está en formato apaisado |
|
|  | [getHeight()](#getHeight--) | Obtiene la altura de la página |
|
|  | [getWidth()](#getWidth--) | Obtiene el ancho de la página |
|
|  | [getTableOfContents()](#getTableOfContents--) | Obtiene la tabla de contenidos |
|
|  | [setTableOfContents(List<TableOfContentsItem> tableOfContents)](#setTableOfContents-java.util.List-com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem--) | Establece la tabla de contenidos |
|
### PdfDocumentInfo(Document pdf, FileType format, long size) {#PdfDocumentInfo-com.aspose.pdf.Document-com.groupdocs.conversion.filetypes.FileType-long-}
```
public PdfDocumentInfo(Document pdf, FileType format, long size)
```


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pdf | com.aspose.pdf.Document |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |

### getVersion() {#getVersion--}
```
public String getVersion()
```


Obtiene la versión


**Returns:**
java.lang.String - versión

### getTitle() {#getTitle--}
```
public String getTitle()
```


Obtiene el título


**Returns:**
java.lang.String - title

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


Obtiene si está encriptado


**Returns:**
boolean - true si está encriptado

### isLandscape() {#isLandscape--}
```
public boolean isLandscape()
```


Obtiene si la página está en formato apaisado


**Returns:**
boolean - true si la página está en formato apaisado

### getHeight() {#getHeight--}
```
public double getHeight()
```


Obtiene la altura de la página


**Returns:**
double - altura de la página

### getWidth() {#getWidth--}
```
public double getWidth()
```


Obtiene el ancho de la página


**Returns:**
double - ancho de la página

### getTableOfContents() {#getTableOfContents--}
```
public List<TableOfContentsItem> getTableOfContents()
```


Obtiene la tabla de contenidos


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem> - tabla de contenidos

### setTableOfContents(List<TableOfContentsItem> tableOfContents) {#setTableOfContents-java.util.List-com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem--}
```
public void setTableOfContents(List<TableOfContentsItem> tableOfContents)
```


Establece la tabla de contenidos


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | tableOfContents | java.util.List<com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem> | Tabla de contenidos |
|

