---
title: "EmailDocumentInfo"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Περιέχει μεταδεδομένα εγγράφου Email"
type: docs
weight: 17
url: /el/java/com.groupdocs.conversion.contracts.documentinfo/emaildocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class EmailDocumentInfo extends DocumentInfo
```

Περιέχει μεταδεδομένα εγγράφου Email

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [EmailDocumentInfo(MailMessage mail, FileType format, long size)](#EmailDocumentInfo-com.aspose.email.MailMessage-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [isSigned()](#isSigned--) | Λαμβάνει αν είναι υπογεγραμμένο |
|
|  | [isEncrypted()](#isEncrypted--) | Λαμβάνει αν είναι κρυπτογραφημένο |
|
|  | [isHtml()](#isHtml--) | Λαμβάνει αν είναι html |
|
|  | [getAttachmentsCount()](#getAttachmentsCount--) | Λαμβάνει αριθμό συνημμένων |
|
|  | [getAttachmentsNames()](#getAttachmentsNames--) | Λαμβάνει ονόματα συνημμένων |
|
### EmailDocumentInfo(MailMessage mail, FileType format, long size) {#EmailDocumentInfo-com.aspose.email.MailMessage-com.groupdocs.conversion.filetypes.FileType-long-}
```
public EmailDocumentInfo(MailMessage mail, FileType format, long size)
```


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| αλληλογραφία | com.aspose.email.MailMessage |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| μέγεθος | long |  |

### isSigned() {#isSigned--}
```
public boolean isSigned()
```


Λαμβάνει αν είναι υπογεγραμμένο


**Returns:**
boolean - true αν είναι υπογεγραμμένο

### isEncrypted() {#isEncrypted--}
```
public boolean isEncrypted()
```


Λαμβάνει αν είναι κρυπτογραφημένο


**Returns:**
boolean - true αν είναι κρυπτογραφημένο

### isHtml() {#isHtml--}
```
public boolean isHtml()
```


Λαμβάνει αν είναι html


**Returns:**
boolean - true αν είναι html

### getAttachmentsCount() {#getAttachmentsCount--}
```
public int getAttachmentsCount()
```


Λαμβάνει αριθμό συνημμένων


**Returns:**
int - αριθμός συνημμένων

### getAttachmentsNames() {#getAttachmentsNames--}
```
public List<String> getAttachmentsNames()
```


Λαμβάνει ονόματα συνημμένων


**Returns:**
java.util.List<java.lang.String> - ονόματα συνημμένων

