---
title: "PresentationDocumentInfo"
second_title: "GroupDocs.Conversion för Java API-referens"
description: "Innehåller metadata för Presentation-dokument"
type: docs
weight: 31
url: /sv/java/com.groupdocs.conversion.contracts.documentinfo/presentationdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class PresentationDocumentInfo extends DocumentInfo
```

Innehåller metadata för Presentation-dokument

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [PresentationDocumentInfo(Presentation presentation, FileType format, long size, boolean isPasswordProtected)](#PresentationDocumentInfo-com.aspose.slides.Presentation-com.groupdocs.conversion.filetypes.FileType-long-boolean-) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getTitle()](#getTitle--) | Hämtar titel |
|
|  | [setTitle(String title)](#setTitle-java.lang.String-) | Ställer in titel |
|
|  | [getAuthor()](#getAuthor--) | Hämtar författare |
|
|  | [setAuthor(String author)](#setAuthor-java.lang.String-) | Ställer in författare |
|
|  | [isPasswordProtected()](#isPasswordProtected--) | Hämtar om dokumentet är lösenordsskyddat |
|
### PresentationDocumentInfo(Presentation presentation, FileType format, long size, boolean isPasswordProtected) {#PresentationDocumentInfo-com.aspose.slides.Presentation-com.groupdocs.conversion.filetypes.FileType-long-boolean-}
```
public PresentationDocumentInfo(Presentation presentation, FileType format, long size, boolean isPasswordProtected)
```


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| presentation | com.aspose.slides.Presentation |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| storlek | long |  |
| isPasswordProtected | boolean |  |

### getTitle() {#getTitle--}
```
public String getTitle()
```


Hämtar titel


**Returns:**
java.lang.String - titel

### setTitle(String title) {#setTitle-java.lang.String-}
```
public void setTitle(String title)
```


Ställer in titel


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | title | java.lang.String | title |
|

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


Ställer in författare


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | författare | java.lang.String | författare |
|

### isPasswordProtected() {#isPasswordProtected--}
```
public boolean isPasswordProtected()
```


Hämtar om dokumentet är lösenordsskyddat


**Returns:**
boolean - `true` om dokumentet är lösenordsskyddat

