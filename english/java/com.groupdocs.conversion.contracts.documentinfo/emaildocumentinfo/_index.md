---
title: EmailDocumentInfo
second_title: GroupDocs.Conversion for Java API Reference
description: Contains Email document metadata
type: docs
weight: 17
url: /java/com.groupdocs.conversion.contracts.documentinfo/emaildocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class EmailDocumentInfo extends DocumentInfo
```

Contains Email document metadata
## Constructors

| Constructor | Description |
| --- | --- |
| [EmailDocumentInfo(MailMessage mail, FileType format, long size)](#EmailDocumentInfo-com.aspose.email.MailMessage-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Methods

| Method | Description |
| --- | --- |
| [isSigned()](#isSigned--) | Gets is signed |
| [isEncrypted()](#isEncrypted--) | Gets is encrypted |
| [isHtml()](#isHtml--) | Gets is html |
| [getAttachmentsCount()](#getAttachmentsCount--) | Gets attachments count |
| [getAttachmentsNames()](#getAttachmentsNames--) | Gets attachments names |
### EmailDocumentInfo(MailMessage mail, FileType format, long size) {#EmailDocumentInfo-com.aspose.email.MailMessage-com.groupdocs.conversion.filetypes.FileType-long-}
```
public EmailDocumentInfo(MailMessage mail, FileType format, long size)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mail | com.aspose.email.MailMessage |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |

### isSigned() {#isSigned--}
```
public boolean isSigned()
```


Gets is signed

**Returns:**
boolean - true if is signed
### isEncrypted() {#isEncrypted--}
```
public boolean isEncrypted()
```


Gets is encrypted

**Returns:**
boolean - true if is encrypted
### isHtml() {#isHtml--}
```
public boolean isHtml()
```


Gets is html

**Returns:**
boolean - true if is html
### getAttachmentsCount() {#getAttachmentsCount--}
```
public int getAttachmentsCount()
```


Gets attachments count

**Returns:**
int - attachments count
### getAttachmentsNames() {#getAttachmentsNames--}
```
public List<String> getAttachmentsNames()
```


Gets attachments names

**Returns:**
java.util.List<java.lang.String> - attachments names
