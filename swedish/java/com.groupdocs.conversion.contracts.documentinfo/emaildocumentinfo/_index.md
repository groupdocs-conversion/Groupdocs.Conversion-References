---
title: "EmailDocumentInfo"
second_title: "GroupDocs.Conversion för Java API-referens"
description: "Innehåller metadata för Email‑dokument"
type: docs
weight: 17
url: /sv/java/com.groupdocs.conversion.contracts.documentinfo/emaildocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class EmailDocumentInfo extends DocumentInfo
```

Innehåller metadata för Email‑dokument

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmailDocumentInfo(MailMessage mail, FileType format, long size)](#EmailDocumentInfo-com.aspose.email.MailMessage-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [isSigned()](#isSigned--) | Hämtar är signerat |
|
|  | [isEncrypted()](#isEncrypted--) | Hämtar om krypterad |
|
|  | [isHtml()](#isHtml--) | Hämtar är HTML |
|
|  | [getAttachmentsCount()](#getAttachmentsCount--) | Hämtar antal bilagor |
|
|  | [getAttachmentsNames()](#getAttachmentsNames--) | Hämtar bilagornas namn |
|
### EmailDocumentInfo(MailMessage mail, FileType format, long size) {#EmailDocumentInfo-com.aspose.email.MailMessage-com.groupdocs.conversion.filetypes.FileType-long-}
```
public EmailDocumentInfo(MailMessage mail, FileType format, long size)
```


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| e-post | com.aspose.email.MailMessage |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| storlek | long |  |

### isSigned() {#isSigned--}
```
public boolean isSigned()
```


Hämtar är signerat


**Returns:**
boolesk - true om den är signerad

### isEncrypted() {#isEncrypted--}
```
public boolean isEncrypted()
```


Hämtar om krypterad


**Returns:**
boolesk - true om den är krypterad

### isHtml() {#isHtml--}
```
public boolean isHtml()
```


Hämtar är HTML


**Returns:**
boolesk - true om den är HTML

### getAttachmentsCount() {#getAttachmentsCount--}
```
public int getAttachmentsCount()
```


Hämtar antal bilagor


**Returns:**
int - antal bilagor

### getAttachmentsNames() {#getAttachmentsNames--}
```
public List<String> getAttachmentsNames()
```


Hämtar bilagornas namn


**Returns:**
java.util.List<java.lang.String> - bilagornas namn

