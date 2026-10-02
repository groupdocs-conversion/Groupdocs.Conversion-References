---
title: "EmailDocumentInfo"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "يحتوي على بيانات تعريف مستند Email"
type: docs
weight: 17
url: /ar/java/com.groupdocs.conversion.contracts.documentinfo/emaildocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class EmailDocumentInfo extends DocumentInfo
```

يحتوي على بيانات تعريف مستند Email

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [EmailDocumentInfo(MailMessage mail, FileType format, long size)](#EmailDocumentInfo-com.aspose.email.MailMessage-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [isSigned()](#isSigned--) | يحصل إذا كان موقّعًا |
|
|  | [isEncrypted()](#isEncrypted--) | يسترجع ما إذا كان مشفرًا |
|
|  | [isHtml()](#isHtml--) | يحصل إذا كان HTML |
|
|  | [getAttachmentsCount()](#getAttachmentsCount--) | يحصل على عدد المرفقات |
|
|  | [getAttachmentsNames()](#getAttachmentsNames--) | يحصل على أسماء المرفقات |
|
### EmailDocumentInfo(MailMessage mail, FileType format, long size) {#EmailDocumentInfo-com.aspose.email.MailMessage-com.groupdocs.conversion.filetypes.FileType-long-}
```
public EmailDocumentInfo(MailMessage mail, FileType format, long size)
```


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بريد | com.aspose.email.MailMessage |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |

### isSigned() {#isSigned--}
```
public boolean isSigned()
```


يحصل إذا كان موقّعًا


**Returns:**
منطقي - true إذا كان موقّعًا

### isEncrypted() {#isEncrypted--}
```
public boolean isEncrypted()
```


يسترجع ما إذا كان مشفرًا


**Returns:**
منطقي - true إذا كان مشفّرًا

### isHtml() {#isHtml--}
```
public boolean isHtml()
```


يحصل إذا كان HTML


**Returns:**
منطقي - true إذا كان HTML

### getAttachmentsCount() {#getAttachmentsCount--}
```
public int getAttachmentsCount()
```


يحصل على عدد المرفقات


**Returns:**
عدد صحيح - عدد المرفقات

### getAttachmentsNames() {#getAttachmentsNames--}
```
public List<String> getAttachmentsNames()
```


يحصل على أسماء المرفقات


**Returns:**
java.util.List<java.lang.String> - أسماء المرفقات

