---
title: "EmailDocumentInfo"
second_title: "GroupDocs.Conversion för Node.js via Java API-referens"
description: "Innehåller metadata för e-postdokument"
type: docs
weight: 17
url: /sv/nodejs-java/com.groupdocs.conversion.contracts.documentinfo/emaildocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class EmailDocumentInfo extends DocumentInfo
```

Innehåller metadata för e-postdokument
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmailDocumentInfo(MailMessage mail, FileType format, long size)](#EmailDocumentInfo-com.aspose.email.MailMessage-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [isSigned()](#isSigned--) | Hämtar om signerat |
| [isEncrypted()](#isEncrypted--) | Hämtar om krypterad |
| [isHtml()](#isHtml--) | Hämtar om HTML |
| [getAttachmentsCount()](#getAttachmentsCount--) | Hämtar antalet bilagor |
| [getAttachmentsNames()](#getAttachmentsNames--) | Hämtar bilagornas namn |
### EmailDocumentInfo(MailMessage mail, FileType format, long size) {#EmailDocumentInfo-com.aspose.email.MailMessage-com.groupdocs.conversion.filetypes.FileType-long-}
```
public EmailDocumentInfo(MailMessage mail, FileType format, long size)
```


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mail | com.aspose.email.MailMessage |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |

### isSigned() {#isSigned--}
```
public boolean isSigned()
```


Hämtar om signerat

**Returns:**
boolean - true om signerat
### isEncrypted() {#isEncrypted--}
```
public boolean isEncrypted()
```


Hämtar om krypterad

**Returns:**
boolean - true om krypterad
### isHtml() {#isHtml--}
```
public boolean isHtml()
```


Hämtar om HTML

**Returns:**
boolean - true om HTML
### getAttachmentsCount() {#getAttachmentsCount--}
```
public int getAttachmentsCount()
```


Hämtar antalet bilagor

**Returns:**
int - antalet bilagor
### getAttachmentsNames() {#getAttachmentsNames--}
```
public List<String> getAttachmentsNames()
```


Hämtar bilagornas namn

**Returns:**
java.util.List<java.lang.String> - bilagornas namn
