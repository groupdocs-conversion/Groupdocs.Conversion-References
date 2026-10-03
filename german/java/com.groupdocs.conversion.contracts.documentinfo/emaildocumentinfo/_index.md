---
title: "EmailDocumentInfo"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Enthält Metadaten für E‑Mail-Dokumente"
type: docs
weight: 17
url: /de/java/com.groupdocs.conversion.contracts.documentinfo/emaildocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class EmailDocumentInfo extends DocumentInfo
```

Enthält Metadaten für E‑Mail-Dokumente

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmailDocumentInfo(MailMessage mail, FileType format, long size)](#EmailDocumentInfo-com.aspose.email.MailMessage-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [isSigned()](#isSigned--) | Ermittelt, ob signiert |
|
|  | [isEncrypted()](#isEncrypted--) | Liefert, ob verschlüsselt ist |
|
|  | [isHtml()](#isHtml--) | Ermittelt, ob HTML |
|
|  | [getAttachmentsCount()](#getAttachmentsCount--) | Ermittelt die Anzahl der Anhänge |
|
|  | [getAttachmentsNames()](#getAttachmentsNames--) | Ermittelt die Namen der Anhänge |
|
### EmailDocumentInfo(MailMessage mail, FileType format, long size) {#EmailDocumentInfo-com.aspose.email.MailMessage-com.groupdocs.conversion.filetypes.FileType-long-}
```
public EmailDocumentInfo(MailMessage mail, FileType format, long size)
```


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Mail | com.aspose.email.MailMessage |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| Größe | long |  |

### isSigned() {#isSigned--}
```
public boolean isSigned()
```


Ermittelt, ob signiert


**Returns:**
boolean - true, wenn signiert

### isEncrypted() {#isEncrypted--}
```
public boolean isEncrypted()
```


Liefert, ob verschlüsselt ist


**Returns:**
boolean - true, wenn verschlüsselt

### isHtml() {#isHtml--}
```
public boolean isHtml()
```


Ermittelt, ob HTML


**Returns:**
boolean - true, wenn HTML

### getAttachmentsCount() {#getAttachmentsCount--}
```
public int getAttachmentsCount()
```


Ermittelt die Anzahl der Anhänge


**Returns:**
int - Anzahl der Anhänge

### getAttachmentsNames() {#getAttachmentsNames--}
```
public List<String> getAttachmentsNames()
```


Ermittelt die Namen der Anhänge


**Returns:**
java.util.List<java.lang.String> - Namen der Anhänge

