---
title: "PresentationDocumentInfo"
second_title: "GroupDocs.Conversion voor Java API-referentie"
description: "Bevat metadata van presentatiedocument"
type: docs
weight: 31
url: /nl/java/com.groupdocs.conversion.contracts.documentinfo/presentationdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class PresentationDocumentInfo extends DocumentInfo
```

Bevat metadata van presentatiedocument

## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [PresentationDocumentInfo(Presentation presentation, FileType format, long size, boolean isPasswordProtected)](#PresentationDocumentInfo-com.aspose.slides.Presentation-com.groupdocs.conversion.filetypes.FileType-long-boolean-) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getTitle()](#getTitle--) | Haalt titel op |
|
|  | [setTitle(String title)](#setTitle-java.lang.String-) | Stelt titel in |
|
|  | [getAuthor()](#getAuthor--) | Haalt auteur op |
|
|  | [setAuthor(String author)](#setAuthor-java.lang.String-) | Stelt auteur in |
|
|  | [isPasswordProtected()](#isPasswordProtected--) | Haalt op of het document met wachtwoord beschermd is |
|
### PresentationDocumentInfo(Presentation presentation, FileType format, long size, boolean isPasswordProtected) {#PresentationDocumentInfo-com.aspose.slides.Presentation-com.groupdocs.conversion.filetypes.FileType-long-boolean-}
```
public PresentationDocumentInfo(Presentation presentation, FileType format, long size, boolean isPasswordProtected)
```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| presentatie | com.aspose.slides.Presentation |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |
| isPasswordProtected | boolean |  |

### getTitle() {#getTitle--}
```
public String getTitle()
```


Haalt titel op


**Returns:**
java.lang.String - titel

### setTitle(String title) {#setTitle-java.lang.String-}
```
public void setTitle(String title)
```


Stelt titel in


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | titel | java.lang.String | titel |
|

### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


Haalt auteur op


**Returns:**
java.lang.String - auteur

### setAuthor(String author) {#setAuthor-java.lang.String-}
```
public void setAuthor(String author)
```


Stelt auteur in


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | auteur | java.lang.String | auteur |
|

### isPasswordProtected() {#isPasswordProtected--}
```
public boolean isPasswordProtected()
```


Haalt op of het document met wachtwoord beschermd is


**Returns:**
boolean - `true` als document met wachtwoord beschermd is

