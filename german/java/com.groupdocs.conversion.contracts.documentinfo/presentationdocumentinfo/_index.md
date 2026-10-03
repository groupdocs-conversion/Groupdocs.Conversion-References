---
title: "PresentationDocumentInfo"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Enthält Metadaten des Präsentationsdokuments"
type: docs
weight: 31
url: /de/java/com.groupdocs.conversion.contracts.documentinfo/presentationdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class PresentationDocumentInfo extends DocumentInfo
```

Enthält Metadaten des Präsentationsdokuments

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PresentationDocumentInfo(Presentation presentation, FileType format, long size, boolean isPasswordProtected)](#PresentationDocumentInfo-com.aspose.slides.Presentation-com.groupdocs.conversion.filetypes.FileType-long-boolean-) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getTitle()](#getTitle--) | Liest Titel |
|
|  | [setTitle(String title)](#setTitle-java.lang.String-) | Setzt den Titel |
|
|  | [getAuthor()](#getAuthor--) | Ermittelt den Autor |
|
|  | [setAuthor(String author)](#setAuthor-java.lang.String-) | Setzt den Autor |
|
|  | [isPasswordProtected()](#isPasswordProtected--) | Ermittelt, ob das Dokument passwortgeschützt ist |
|
### PresentationDocumentInfo(Presentation presentation, FileType format, long size, boolean isPasswordProtected) {#PresentationDocumentInfo-com.aspose.slides.Presentation-com.groupdocs.conversion.filetypes.FileType-long-boolean-}
```
public PresentationDocumentInfo(Presentation presentation, FileType format, long size, boolean isPasswordProtected)
```


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Präsentation | com.aspose.slides.Presentation |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| Größe | long |  |
| isPasswordProtected | boolean |  |

### getTitle() {#getTitle--}
```
public String getTitle()
```


Liest Titel


**Returns:**
java.lang.String - Titel

### setTitle(String title) {#setTitle-java.lang.String-}
```
public void setTitle(String title)
```


Setzt den Titel


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Titel | java.lang.String | Titel |
|

### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


Ermittelt den Autor


**Returns:**
java.lang.String - Autor

### setAuthor(String author) {#setAuthor-java.lang.String-}
```
public void setAuthor(String author)
```


Setzt den Autor


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Autor | java.lang.String | Autor |
|

### isPasswordProtected() {#isPasswordProtected--}
```
public boolean isPasswordProtected()
```


Ermittelt, ob das Dokument passwortgeschützt ist


**Returns:**
boolean - `true` wenn das Dokument passwortgeschützt ist

