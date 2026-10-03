---
title: "EmailDocumentInfo"
second_title: "Referencia de API de GroupDocs.Conversion for Java"
description: "Contiene metadatos del documento de Email"
type: docs
weight: 17
url: /es/java/com.groupdocs.conversion.contracts.documentinfo/emaildocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class EmailDocumentInfo extends DocumentInfo
```

Contiene metadatos del documento de Email

## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmailDocumentInfo(MailMessage mail, FileType format, long size)](#EmailDocumentInfo-com.aspose.email.MailMessage-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [isSigned()](#isSigned--) | Obtiene si está firmado |
|
|  | [isEncrypted()](#isEncrypted--) | Obtiene si está encriptado |
|
|  | [isHtml()](#isHtml--) | Obtiene si es HTML |
|
|  | [getAttachmentsCount()](#getAttachmentsCount--) | Obtiene el número de adjuntos |
|
|  | [getAttachmentsNames()](#getAttachmentsNames--) | Obtiene los nombres de los adjuntos |
|
### EmailDocumentInfo(MailMessage mail, FileType format, long size) {#EmailDocumentInfo-com.aspose.email.MailMessage-com.groupdocs.conversion.filetypes.FileType-long-}
```
public EmailDocumentInfo(MailMessage mail, FileType format, long size)
```


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| correo | com.aspose.email.MailMessage |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |

### isSigned() {#isSigned--}
```
public boolean isSigned()
```


Obtiene si está firmado


**Returns:**
boolean - verdadero si está firmado

### isEncrypted() {#isEncrypted--}
```
public boolean isEncrypted()
```


Obtiene si está encriptado


**Returns:**
boolean - verdadero si está encriptado

### isHtml() {#isHtml--}
```
public boolean isHtml()
```


Obtiene si es HTML


**Returns:**
boolean - verdadero si es HTML

### getAttachmentsCount() {#getAttachmentsCount--}
```
public int getAttachmentsCount()
```


Obtiene el número de adjuntos


**Returns:**
int - número de adjuntos

### getAttachmentsNames() {#getAttachmentsNames--}
```
public List<String> getAttachmentsNames()
```


Obtiene los nombres de los adjuntos


**Returns:**
java.util.List<java.lang.String> - nombres de los adjuntos

