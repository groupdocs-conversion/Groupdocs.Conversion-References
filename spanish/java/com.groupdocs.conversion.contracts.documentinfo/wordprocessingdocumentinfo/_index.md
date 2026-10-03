---
title: "WordProcessingDocumentInfo"
second_title: "Referencia de API de GroupDocs.Conversion for Java"
description: "Contiene metadatos del documento de procesamiento de texto"
type: docs
weight: 45
url: /es/java/com.groupdocs.conversion.contracts.documentinfo/wordprocessingdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class WordProcessingDocumentInfo extends DocumentInfo
```

Contiene metadatos del documento de procesamiento de texto

## Constructores

| Constructor | Descripción |
| --- | --- |
| [WordProcessingDocumentInfo(Document wordprocessing, boolean isPasswordProtected, FileType format, long size)](#WordProcessingDocumentInfo-com.aspose.words.Document-boolean-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getWords()](#getWords--) | Obtiene el recuento de palabras |
|
|  | [getLines()](#getLines--) | Obtiene el recuento de líneas |
|
|  | [getTitle()](#getTitle--) | Obtiene el título |
|
|  | [getAuthor()](#getAuthor--) | Obtiene el autor |
|
|  | [isPasswordProtected()](#isPasswordProtected--) | Obtiene si el documento está protegido con contraseña |
|
|  | [getTableOfContents()](#getTableOfContents--) | Tabla de contenidos |
|
### WordProcessingDocumentInfo(Document wordprocessing, boolean isPasswordProtected, FileType format, long size) {#WordProcessingDocumentInfo-com.aspose.words.Document-boolean-com.groupdocs.conversion.filetypes.FileType-long-}
```
public WordProcessingDocumentInfo(Document wordprocessing, boolean isPasswordProtected, FileType format, long size)
```


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| procesamiento de texto | com.aspose.words.Document |  |
| isPasswordProtected | booleano |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |

### getWords() {#getWords--}
```
public int getWords()
```


Obtiene el recuento de palabras


**Returns:**
int - recuento de palabras

### getLines() {#getLines--}
```
public int getLines()
```


Obtiene el recuento de líneas


**Returns:**
int - recuento de líneas

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


Obtiene si el documento está protegido con contraseña


**Returns:**
boolean - `true` si el documento está protegido con contraseña

### getTableOfContents() {#getTableOfContents--}
```
public List<TableOfContentsItem> getTableOfContents()
```


Tabla de contenidos


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem> - tabla de contenidos

