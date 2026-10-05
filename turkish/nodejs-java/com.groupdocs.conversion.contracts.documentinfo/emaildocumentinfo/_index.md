---
title: "EmailDocumentInfo"
second_title: "Node.js için GroupDocs.Conversion, Java üzerinden API Referansı"
description: "Email belge üst verilerini içerir"
type: docs
weight: 17
url: /tr/nodejs-java/com.groupdocs.conversion.contracts.documentinfo/emaildocumentinfo/
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
| [isSigned()](#isSigned--) | İmzalı olup olmadığını alır |
| [isEncrypted()](#isEncrypted--) | Şifrelenmiş olup olduğunu alır |
| [isHtml()](#isHtml--) | HTML olup olmadığını alır |
| [getAttachmentsCount()](#getAttachmentsCount--) | Ek sayısını alır |
| [getAttachmentsNames()](#getAttachmentsNames--) | Ek adlarını alır |
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


İmzalı olup olmadığını alır

**Returns:**
boolean - imzalıysa doğru
### isEncrypted() {#isEncrypted--}
```
public boolean isEncrypted()
```


Şifrelenmiş olup olduğunu alır

**Returns:**
boolean - şifrelenmişse doğru
### isHtml() {#isHtml--}
```
public boolean isHtml()
```


HTML olup olmadığını alır

**Returns:**
boolean - HTML ise doğru
### getAttachmentsCount() {#getAttachmentsCount--}
```
public int getAttachmentsCount()
```


Ek sayısını alır

**Returns:**
int - ek sayısı
### getAttachmentsNames() {#getAttachmentsNames--}
```
public List<String> getAttachmentsNames()
```


Ek adlarını alır

**Returns:**
java.util.List<java.lang.String> - ek adları
