---
title: "EmailDocumentInfo"
second_title: "Справочник API GroupDocs.Conversion for Java"
description: "Содержит метаданные электронного письма"
type: docs
weight: 17
url: /ru/java/com.groupdocs.conversion.contracts.documentinfo/emaildocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class EmailDocumentInfo extends DocumentInfo
```

Содержит метаданные электронного письма

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmailDocumentInfo(MailMessage mail, FileType format, long size)](#EmailDocumentInfo-com.aspose.email.MailMessage-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [isSigned()](#isSigned--) | Получает, подписан |
|
|  | [isEncrypted()](#isEncrypted--) | Получает, зашифровано |
|
|  | [isHtml()](#isHtml--) | Получает, является HTML |
|
|  | [getAttachmentsCount()](#getAttachmentsCount--) | Получает количество вложений |
|
|  | [getAttachmentsNames()](#getAttachmentsNames--) | Получает имена вложений |
|
### EmailDocumentInfo(MailMessage mail, FileType format, long size) {#EmailDocumentInfo-com.aspose.email.MailMessage-com.groupdocs.conversion.filetypes.FileType-long-}
```
public EmailDocumentInfo(MailMessage mail, FileType format, long size)
```


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| почта | com.aspose.email.MailMessage |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |

### isSigned() {#isSigned--}
```
public boolean isSigned()
```


Получает, подписан


**Returns:**
boolean - true, если подписан

### isEncrypted() {#isEncrypted--}
```
public boolean isEncrypted()
```


Получает, зашифровано


**Returns:**
boolean - true, если зашифрован

### isHtml() {#isHtml--}
```
public boolean isHtml()
```


Получает, является HTML


**Returns:**
boolean - true, если HTML

### getAttachmentsCount() {#getAttachmentsCount--}
```
public int getAttachmentsCount()
```


Получает количество вложений


**Returns:**
int - количество вложений

### getAttachmentsNames() {#getAttachmentsNames--}
```
public List<String> getAttachmentsNames()
```


Получает имена вложений


**Returns:**
java.util.List<java.lang.String> - имена вложений

