---
title: "EmailDocumentInfo"
second_title: "GroupDocs.Conversion for Node.js via Java API-referentie"
description: "Bevat e-maildocumentmetadata"
type: docs
weight: 17
url: /nl/nodejs-java/com.groupdocs.conversion.contracts.documentinfo/emaildocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class EmailDocumentInfo extends DocumentInfo
```

Bevat e-maildocumentmetadata
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [EmailDocumentInfo(MailMessage mail, FileType format, long size)](#EmailDocumentInfo-com.aspose.email.MailMessage-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [isSigned()](#isSigned--) | Haalt op is ondertekend |
| [isEncrypted()](#isEncrypted--) | Haalt op of versleuteld is |
| [isHtml()](#isHtml--) | Haalt op is html |
| [getAttachmentsCount()](#getAttachmentsCount--) | Haalt op bijlagen aantal |
| [getAttachmentsNames()](#getAttachmentsNames--) | Haalt op bijlagen namen |
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


Haalt op is ondertekend

**Returns:**
boolean - true als ondertekend
### isEncrypted() {#isEncrypted--}
```
public boolean isEncrypted()
```


Haalt op of versleuteld is

**Returns:**
boolean - true als versleuteld
### isHtml() {#isHtml--}
```
public boolean isHtml()
```


Haalt op is html

**Returns:**
boolean - true als html
### getAttachmentsCount() {#getAttachmentsCount--}
```
public int getAttachmentsCount()
```


Haalt op bijlagen aantal

**Returns:**
int - aantal bijlagen
### getAttachmentsNames() {#getAttachmentsNames--}
```
public List<String> getAttachmentsNames()
```


Haalt op bijlagen namen

**Returns:**
java.util.List<java.lang.String> - bijlagen namen
