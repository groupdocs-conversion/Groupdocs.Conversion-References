---
title: "PresentationDocumentInfo"
second_title: "Referencia de API de GroupDocs.Conversion para Node.js vía Java"
description: "Contiene metadatos del documento Presentation"
type: docs
weight: 34
url: /es/nodejs-java/com.groupdocs.conversion.contracts.documentinfo/presentationdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class PresentationDocumentInfo extends DocumentInfo
```

Contiene metadatos del documento Presentation
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PresentationDocumentInfo(Presentation presentation, FileType format, long size, boolean isPasswordProtected)](#PresentationDocumentInfo-com.aspose.slides.Presentation-com.groupdocs.conversion.filetypes.FileType-long-boolean-) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getTitle()](#getTitle--) | Obtiene el título |
| [setTitle(String title)](#setTitle-java.lang.String-) | Establece el título |
| [getAuthor()](#getAuthor--) | Obtiene el autor |
| [setAuthor(String author)](#setAuthor-java.lang.String-) | Establece el autor |
| [isPasswordProtected()](#isPasswordProtected--) | Obtiene si el documento está protegido con contraseña |
### PresentationDocumentInfo(Presentation presentation, FileType format, long size, boolean isPasswordProtected) {#PresentationDocumentInfo-com.aspose.slides.Presentation-com.groupdocs.conversion.filetypes.FileType-long-boolean-}
```
public PresentationDocumentInfo(Presentation presentation, FileType format, long size, boolean isPasswordProtected)
```


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| presentation | com.aspose.slides.Presentation |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| tamaño | long |  |
| isPasswordProtected | boolean |  |

### getTitle() {#getTitle--}
```
public String getTitle()
```


Obtiene el título

**Returns:**
java.lang.String - título
### setTitle(String title) {#setTitle-java.lang.String-}
```
public void setTitle(String title)
```


Establece el título

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| title | java.lang.String | title |

### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


Obtiene el autor

**Returns:**
java.lang.String - autor
### setAuthor(String author) {#setAuthor-java.lang.String-}
```
public void setAuthor(String author)
```


Establece el autor

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| autor | java.lang.String | autor |

### isPasswordProtected() {#isPasswordProtected--}
```
public boolean isPasswordProtected()
```


Obtiene si el documento está protegido con contraseña

**Returns:**
boolean - `true` si el documento está protegido con contraseña
