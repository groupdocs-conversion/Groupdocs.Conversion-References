---
title: "PresentationDocumentInfo"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Περιέχει μεταδεδομένα εγγράφου παρουσίασης"
type: docs
weight: 31
url: /el/java/com.groupdocs.conversion.contracts.documentinfo/presentationdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class PresentationDocumentInfo extends DocumentInfo
```

Περιέχει μεταδεδομένα εγγράφου παρουσίασης

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [PresentationDocumentInfo(Presentation presentation, FileType format, long size, boolean isPasswordProtected)](#PresentationDocumentInfo-com.aspose.slides.Presentation-com.groupdocs.conversion.filetypes.FileType-long-boolean-) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getTitle()](#getTitle--) | Λαμβάνει τίτλο |
|
|  | [setTitle(String title)](#setTitle-java.lang.String-) | Ορίζει τίτλο |
|
|  | [getAuthor()](#getAuthor--) | Λαμβάνει συγγραφέα |
|
|  | [setAuthor(String author)](#setAuthor-java.lang.String-) | Ορίζει συγγραφέα |
|
|  | [isPasswordProtected()](#isPasswordProtected--) | Λαμβάνει αν το έγγραφο είναι προστατευμένο με κωδικό |
|
### PresentationDocumentInfo(Presentation presentation, FileType format, long size, boolean isPasswordProtected) {#PresentationDocumentInfo-com.aspose.slides.Presentation-com.groupdocs.conversion.filetypes.FileType-long-boolean-}
```
public PresentationDocumentInfo(Presentation presentation, FileType format, long size, boolean isPasswordProtected)
```


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| παρουσίαση | com.aspose.slides.Presentation |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| μέγεθος | long |  |
| isPasswordProtected | boolean |  |

### getTitle() {#getTitle--}
```
public String getTitle()
```


Λαμβάνει τίτλο


**Returns:**
java.lang.String - τίτλος

### setTitle(String title) {#setTitle-java.lang.String-}
```
public void setTitle(String title)
```


Ορίζει τίτλο


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | τίτλος | java.lang.String | τίτλος |
|

### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


Λαμβάνει συγγραφέα


**Returns:**
java.lang.String - συγγραφέας

### setAuthor(String author) {#setAuthor-java.lang.String-}
```
public void setAuthor(String author)
```


Ορίζει συγγραφέα


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | συγγραφέας | java.lang.String | συγγραφέας |
|

### isPasswordProtected() {#isPasswordProtected--}
```
public boolean isPasswordProtected()
```


Λαμβάνει αν το έγγραφο είναι προστατευμένο με κωδικό


**Returns:**
boolean - `true` εάν το έγγραφο είναι προστατευμένο με κωδικό

