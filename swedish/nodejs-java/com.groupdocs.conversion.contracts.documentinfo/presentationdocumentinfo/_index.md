---
title: "PresentationDocumentInfo"
second_title: "GroupDocs.Conversion för Node.js via Java API-referens"
description: "Innehåller Presentation-dokumentmetadata"
type: docs
weight: 34
url: /sv/nodejs-java/com.groupdocs.conversion.contracts.documentinfo/presentationdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class PresentationDocumentInfo extends DocumentInfo
```

Innehåller Presentation-dokumentmetadata
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [PresentationDocumentInfo(Presentation presentation, FileType format, long size, boolean isPasswordProtected)](#PresentationDocumentInfo-com.aspose.slides.Presentation-com.groupdocs.conversion.filetypes.FileType-long-boolean-) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getTitle()](#getTitle--) | Hämtar titel |
| [setTitle(String title)](#setTitle-java.lang.String-) | Sätter titel |
| [getAuthor()](#getAuthor--) | Hämtar författare |
| [setAuthor(String author)](#setAuthor-java.lang.String-) | Sätter författare |
| [isPasswordProtected()](#isPasswordProtected--) | Hämtar om dokumentet är lösenordsskyddat |
### PresentationDocumentInfo(Presentation presentation, FileType format, long size, boolean isPasswordProtected) {#PresentationDocumentInfo-com.aspose.slides.Presentation-com.groupdocs.conversion.filetypes.FileType-long-boolean-}
```
public PresentationDocumentInfo(Presentation presentation, FileType format, long size, boolean isPasswordProtected)
```


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| presentation | com.aspose.slides.Presentation |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |
| isPasswordProtected | boolean |  |

### getTitle() {#getTitle--}
```
public String getTitle()
```


Hämtar titel

**Returns:**
java.lang.String - title
### setTitle(String title) {#setTitle-java.lang.String-}
```
public void setTitle(String title)
```


Sätter titel

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| titel | java.lang.String | titel |

### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


Hämtar författare

**Returns:**
java.lang.String - författare
### setAuthor(String author) {#setAuthor-java.lang.String-}
```
public void setAuthor(String author)
```


Sätter författare

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| författare | java.lang.String | författare |

### isPasswordProtected() {#isPasswordProtected--}
```
public boolean isPasswordProtected()
```


Hämtar om dokumentet är lösenordsskyddat

**Returns:**
boolean - `true` om dokumentet är lösenordsskyddat
