---
title: "EmailDocumentInfo"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "包含电子邮件文档元数据"
type: docs
weight: 17
url: /zh/java/com.groupdocs.conversion.contracts.documentinfo/emaildocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class EmailDocumentInfo extends DocumentInfo
```

包含电子邮件文档元数据

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmailDocumentInfo(MailMessage mail, FileType format, long size)](#EmailDocumentInfo-com.aspose.email.MailMessage-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [isSigned()](#isSigned--) | 获取是否已签名 |
|
|  | [isEncrypted()](#isEncrypted--) | 获取是否已加密 |
|
|  | [isHtml()](#isHtml--) | 获取是否为HTML |
|
|  | [getAttachmentsCount()](#getAttachmentsCount--) | 获取附件数量 |
|
|  | [getAttachmentsNames()](#getAttachmentsNames--) | 获取附件名称 |
|
### EmailDocumentInfo(MailMessage mail, FileType format, long size) {#EmailDocumentInfo-com.aspose.email.MailMessage-com.groupdocs.conversion.filetypes.FileType-long-}
```
public EmailDocumentInfo(MailMessage mail, FileType format, long size)
```


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 邮件 | com.aspose.email.MailMessage |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| 大小 | long |  |

### isSigned() {#isSigned--}
```
public boolean isSigned()
```


获取是否已签名


**Returns:**
布尔型 - 如果已签名则为 true

### isEncrypted() {#isEncrypted--}
```
public boolean isEncrypted()
```


获取是否已加密


**Returns:**
布尔型 - 如果已加密则为 true

### isHtml() {#isHtml--}
```
public boolean isHtml()
```


获取是否为HTML


**Returns:**
布尔型 - 如果是 HTML 则为 true

### getAttachmentsCount() {#getAttachmentsCount--}
```
public int getAttachmentsCount()
```


获取附件数量


**Returns:**
整数型 - 附件数量

### getAttachmentsNames() {#getAttachmentsNames--}
```
public List<String> getAttachmentsNames()
```


获取附件名称


**Returns:**
java.util.List<java.lang.String> - 附件名称

