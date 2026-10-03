---
title: "EmailDocumentInfo"
second_title: "GroupDocs.Conversion voor Java API-referentie"
description: "Bevat metadata van Email-document"
type: docs
weight: 17
url: /nl/java/com.groupdocs.conversion.contracts.documentinfo/emaildocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class EmailDocumentInfo extends DocumentInfo
```

Bevat metadata van Email-document

## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [EmailDocumentInfo(MailMessage mail, FileType format, long size)](#EmailDocumentInfo-com.aspose.email.MailMessage-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [isSigned()](#isSigned--) | Haalt op of ondertekend |
|
|  | [isEncrypted()](#isEncrypted--) | Haalt versleuteld op |
|
|  | [isHtml()](#isHtml--) | Haalt op of HTML |
|
|  | [getAttachmentsCount()](#getAttachmentsCount--) | Haalt aantal bijlagen op |
|
|  | [getAttachmentsNames()](#getAttachmentsNames--) | Haalt namen van bijlagen op |
|
### EmailDocumentInfo(MailMessage mail, FileType format, long size) {#EmailDocumentInfo-com.aspose.email.MailMessage-com.groupdocs.conversion.filetypes.FileType-long-}
```
public EmailDocumentInfo(MailMessage mail, FileType format, long size)
```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mail | com.aspose.email.MailMessage |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |

### isSigned() {#isSigned--}
```
public boolean isSigned()
```


Haalt op of ondertekend


**Returns:**
boolean - true als ondertekend

### isEncrypted() {#isEncrypted--}
```
public boolean isEncrypted()
```


Haalt versleuteld op


**Returns:**
boolean - true als versleuteld

### isHtml() {#isHtml--}
```
public boolean isHtml()
```


Haalt op of HTML


**Returns:**
boolean - true als HTML

### getAttachmentsCount() {#getAttachmentsCount--}
```
public int getAttachmentsCount()
```


Haalt aantal bijlagen op


**Returns:**
int - aantal bijlagen

### getAttachmentsNames() {#getAttachmentsNames--}
```
public List<String> getAttachmentsNames()
```


Haalt namen van bijlagen op


**Returns:**
java.util.List<java.lang.String> - namen van bijlagen

