---
title: "EmailDocumentInfo"
second_title: "Java için GroupDocs.Conversion API Referansı"
description: "Email belge üst verilerini içerir"
type: docs
weight: 17
url: /tr/java/com.groupdocs.conversion.contracts.documentinfo/emaildocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class EmailDocumentInfo extends DocumentInfo
```

Email belge üst verilerini içerir

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmailDocumentInfo(MailMessage mail, FileType format, long size)](#EmailDocumentInfo-com.aspose.email.MailMessage-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [isSigned()](#isSigned--) | Alır imzalı |
|
|  | [isEncrypted()](#isEncrypted--) | Şifrelenmiş mi alır |
|
|  | [isHtml()](#isHtml--) | Alır html |
|
|  | [getAttachmentsCount()](#getAttachmentsCount--) | Alır ek sayısı |
|
|  | [getAttachmentsNames()](#getAttachmentsNames--) | Alır ek adları |
|
### EmailDocumentInfo(MailMessage mail, FileType format, long size) {#EmailDocumentInfo-com.aspose.email.MailMessage-com.groupdocs.conversion.filetypes.FileType-long-}
```
public EmailDocumentInfo(MailMessage mail, FileType format, long size)
```


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| posta | com.aspose.email.MailMessage |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |

### isSigned() {#isSigned--}
```
public boolean isSigned()
```


Alır imzalı


**Returns:**
boolean - doğru ise imzalı

### isEncrypted() {#isEncrypted--}
```
public boolean isEncrypted()
```


Şifrelenmiş mi alır


**Returns:**
boolean - doğru ise şifreli

### isHtml() {#isHtml--}
```
public boolean isHtml()
```


Alır html


**Returns:**
boolean - doğru ise html

### getAttachmentsCount() {#getAttachmentsCount--}
```
public int getAttachmentsCount()
```


Alır ek sayısı


**Returns:**
int - ek sayısı

### getAttachmentsNames() {#getAttachmentsNames--}
```
public List<String> getAttachmentsNames()
```


Alır ek adları


**Returns:**
java.util.List<java.lang.String> - ek adları

