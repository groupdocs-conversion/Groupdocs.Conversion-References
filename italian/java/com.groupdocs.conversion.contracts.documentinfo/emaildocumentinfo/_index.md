---
title: "EmailDocumentInfo"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Contiene i metadati del documento Email"
type: docs
weight: 17
url: /it/java/com.groupdocs.conversion.contracts.documentinfo/emaildocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class EmailDocumentInfo extends DocumentInfo
```

Contiene i metadati del documento Email

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmailDocumentInfo(MailMessage mail, FileType format, long size)](#EmailDocumentInfo-com.aspose.email.MailMessage-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [isSigned()](#isSigned--) | Ottiene se è firmato |
|
|  | [isEncrypted()](#isEncrypted--) | Ottiene se è crittografato |
|
|  | [isHtml()](#isHtml--) | Ottiene se è html |
|
|  | [getAttachmentsCount()](#getAttachmentsCount--) | Ottiene il conteggio degli allegati |
|
|  | [getAttachmentsNames()](#getAttachmentsNames--) | Ottiene i nomi degli allegati |
|
### EmailDocumentInfo(MailMessage mail, FileType format, long size) {#EmailDocumentInfo-com.aspose.email.MailMessage-com.groupdocs.conversion.filetypes.FileType-long-}
```
public EmailDocumentInfo(MailMessage mail, FileType format, long size)
```


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| posta | com.aspose.email.MailMessage |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| dimensione | long |  |

### isSigned() {#isSigned--}
```
public boolean isSigned()
```


Ottiene se è firmato


**Returns:**
boolean - true se è firmato

### isEncrypted() {#isEncrypted--}
```
public boolean isEncrypted()
```


Ottiene se è crittografato


**Returns:**
boolean - true se è crittografato

### isHtml() {#isHtml--}
```
public boolean isHtml()
```


Ottiene se è html


**Returns:**
boolean - true se è html

### getAttachmentsCount() {#getAttachmentsCount--}
```
public int getAttachmentsCount()
```


Ottiene il conteggio degli allegati


**Returns:**
int - conteggio degli allegati

### getAttachmentsNames() {#getAttachmentsNames--}
```
public List<String> getAttachmentsNames()
```


Ottiene i nomi degli allegati


**Returns:**
java.util.List<java.lang.String> - nomi degli allegati

