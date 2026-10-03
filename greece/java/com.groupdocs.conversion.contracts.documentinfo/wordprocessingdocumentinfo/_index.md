---
title: "WordProcessingDocumentInfo"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Περιέχει μεταδεδομένα εγγράφου επεξεργασίας κειμένου"
type: docs
weight: 45
url: /el/java/com.groupdocs.conversion.contracts.documentinfo/wordprocessingdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class WordProcessingDocumentInfo extends DocumentInfo
```

Περιέχει μεταδεδομένα εγγράφου επεξεργασίας κειμένου

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [WordProcessingDocumentInfo(Document wordprocessing, boolean isPasswordProtected, FileType format, long size)](#WordProcessingDocumentInfo-com.aspose.words.Document-boolean-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getWords()](#getWords--) | Λαμβάνει τον αριθμό των λέξεων |
|
|  | [getLines()](#getLines--) | Λαμβάνει τον αριθμό των γραμμών |
|
|  | [getTitle()](#getTitle--) | Λαμβάνει τίτλο |
|
|  | [getAuthor()](#getAuthor--) | Λαμβάνει συγγραφέα |
|
|  | [isPasswordProtected()](#isPasswordProtected--) | Λαμβάνει εάν το έγγραφο είναι προστατευμένο με κωδικό |
|
|  | [getTableOfContents()](#getTableOfContents--) | Πίνακας περιεχομένων |
|
### WordProcessingDocumentInfo(Document wordprocessing, boolean isPasswordProtected, FileType format, long size) {#WordProcessingDocumentInfo-com.aspose.words.Document-boolean-com.groupdocs.conversion.filetypes.FileType-long-}
```
public WordProcessingDocumentInfo(Document wordprocessing, boolean isPasswordProtected, FileType format, long size)
```


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| επεξεργασία κειμένου | com.aspose.words.Document |  |
| isPasswordProtected | boolean |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| μέγεθος | long |  |

### getWords() {#getWords--}
```
public int getWords()
```


Λαμβάνει τον αριθμό των λέξεων


**Returns:**
int - αριθμός λέξεων

### getLines() {#getLines--}
```
public int getLines()
```


Λαμβάνει τον αριθμό των γραμμών


**Returns:**
int - αριθμός γραμμών

### getTitle() {#getTitle--}
```
public String getTitle()
```


Λαμβάνει τίτλο


**Returns:**
java.lang.String - τίτλος

### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


Λαμβάνει συγγραφέα


**Returns:**
java.lang.String - συγγραφέας

### isPasswordProtected() {#isPasswordProtected--}
```
public boolean isPasswordProtected()
```


Λαμβάνει εάν το έγγραφο είναι προστατευμένο με κωδικό


**Returns:**
boolean - `true` εάν το έγγραφο είναι προστατευμένο με κωδικό

### getTableOfContents() {#getTableOfContents--}
```
public List<TableOfContentsItem> getTableOfContents()
```


Πίνακας περιεχομένων


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem> - Πίνακας περιεχομένων

