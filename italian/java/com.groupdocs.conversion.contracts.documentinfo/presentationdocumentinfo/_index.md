---
title: "PresentationDocumentInfo"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Contiene i metadati del documento Presentation"
type: docs
weight: 31
url: /it/java/com.groupdocs.conversion.contracts.documentinfo/presentationdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class PresentationDocumentInfo extends DocumentInfo
```

Contiene i metadati del documento Presentation

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PresentationDocumentInfo(Presentation presentation, FileType format, long size, boolean isPasswordProtected)](#PresentationDocumentInfo-com.aspose.slides.Presentation-com.groupdocs.conversion.filetypes.FileType-long-boolean-) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getTitle()](#getTitle--) | Ottiene il titolo |
|
|  | [setTitle(String title)](#setTitle-java.lang.String-) | Imposta il titolo |
|
|  | [getAuthor()](#getAuthor--) | Ottiene l'autore |
|
|  | [setAuthor(String author)](#setAuthor-java.lang.String-) | Imposta l'autore |
|
|  | [isPasswordProtected()](#isPasswordProtected--) | Ottiene se il documento è protetto da password |
|
### PresentationDocumentInfo(Presentation presentation, FileType format, long size, boolean isPasswordProtected) {#PresentationDocumentInfo-com.aspose.slides.Presentation-com.groupdocs.conversion.filetypes.FileType-long-boolean-}
```
public PresentationDocumentInfo(Presentation presentation, FileType format, long size, boolean isPasswordProtected)
```


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| presentazione | com.aspose.slides.Presentation |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| dimensione | long |  |
| isPasswordProtected | booleano |  |

### getTitle() {#getTitle--}
```
public String getTitle()
```


Ottiene il titolo


**Returns:**
java.lang.String - titolo

### setTitle(String title) {#setTitle-java.lang.String-}
```
public void setTitle(String title)
```


Imposta il titolo


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | title | java.lang.String | title |
|

### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


Ottiene l'autore


**Returns:**
java.lang.String - autore

### setAuthor(String author) {#setAuthor-java.lang.String-}
```
public void setAuthor(String author)
```


Imposta l'autore


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | author | java.lang.String | author |
|

### isPasswordProtected() {#isPasswordProtected--}
```
public boolean isPasswordProtected()
```


Ottiene se il documento è protetto da password


**Returns:**
boolean - `true` se il documento è protetto da password

