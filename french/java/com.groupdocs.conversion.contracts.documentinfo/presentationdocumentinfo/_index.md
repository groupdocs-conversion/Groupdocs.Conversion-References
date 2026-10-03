---
title: "PresentationDocumentInfo"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Contient les métadonnées du document Presentation"
type: docs
weight: 31
url: /fr/java/com.groupdocs.conversion.contracts.documentinfo/presentationdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class PresentationDocumentInfo extends DocumentInfo
```

Contient les métadonnées du document Presentation

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PresentationDocumentInfo(Presentation presentation, FileType format, long size, boolean isPasswordProtected)](#PresentationDocumentInfo-com.aspose.slides.Presentation-com.groupdocs.conversion.filetypes.FileType-long-boolean-) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getTitle()](#getTitle--) | Obtient le titre |
|
|  | [setTitle(String title)](#setTitle-java.lang.String-) | Définit le titre |
|
|  | [getAuthor()](#getAuthor--) | Obtient l'auteur |
|
|  | [setAuthor(String author)](#setAuthor-java.lang.String-) | Définit l'auteur |
|
|  | [isPasswordProtected()](#isPasswordProtected--) | Obtient si le document est protégé par mot de passe |
|
### PresentationDocumentInfo(Presentation presentation, FileType format, long size, boolean isPasswordProtected) {#PresentationDocumentInfo-com.aspose.slides.Presentation-com.groupdocs.conversion.filetypes.FileType-long-boolean-}
```
public PresentationDocumentInfo(Presentation presentation, FileType format, long size, boolean isPasswordProtected)
```


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| présentation | com.aspose.slides.Presentation |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |
| isPasswordProtected | booléen |  |

### getTitle() {#getTitle--}
```
public String getTitle()
```


Obtient le titre


**Returns:**
java.lang.String - titre

### setTitle(String title) {#setTitle-java.lang.String-}
```
public void setTitle(String title)
```


Définit le titre


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | title | java.lang.String | title |
|

### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


Obtient l'auteur


**Returns:**
java.lang.String - auteur

### setAuthor(String author) {#setAuthor-java.lang.String-}
```
public void setAuthor(String author)
```


Définit l'auteur


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | author | java.lang.String | author |
|

### isPasswordProtected() {#isPasswordProtected--}
```
public boolean isPasswordProtected()
```


Obtient si le document est protégé par mot de passe


**Returns:**
boolean - `true` si le document est protégé par mot de passe

