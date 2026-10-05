---
title: "EmailDocumentInfo"
second_title: "Referencia de API de GroupDocs.Conversion para Node.js vía Java"
description: "Contiene metadatos de documento de correo electrónico"
type: docs
weight: 17
url: /es/nodejs-java/com.groupdocs.conversion.contracts.documentinfo/emaildocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class EmailDocumentInfo extends DocumentInfo
```

Contiene metadatos de documento de correo electrónico
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmailDocumentInfo(MailMessage mail, FileType format, long size)](#EmailDocumentInfo-com.aspose.email.MailMessage-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [isSigned()](#isSigned--) | Obtiene si está firmado |
| [isEncrypted()](#isEncrypted--) | Obtiene si está encriptado |
| [isHtml()](#isHtml--) | Obtiene si es html |
| [getAttachmentsCount()](#getAttachmentsCount--) | Obtiene recuento de archivos adjuntos |
| [getAttachmentsNames()](#getAttachmentsNames--) | Obtiene nombres de archivos adjuntos |
### EmailDocumentInfo(MailMessage mail, FileType format, long size) {#EmailDocumentInfo-com.aspose.email.MailMessage-com.groupdocs.conversion.filetypes.FileType-long-}
```
public EmailDocumentInfo(MailMessage mail, FileType format, long size)
```


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| correo | com.aspose.email.MailMessage |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| tamaño | long |  |

### isSigned() {#isSigned--}
```
public boolean isSigned()
```


Obtiene si está firmado

**Returns:**
boolean - true si está firmado
### isEncrypted() {#isEncrypted--}
```
public boolean isEncrypted()
```


Obtiene si está encriptado

**Returns:**
boolean - true si está encriptado
### isHtml() {#isHtml--}
```
public boolean isHtml()
```


Obtiene si es html

**Returns:**
boolean - true si es html
### getAttachmentsCount() {#getAttachmentsCount--}
```
public int getAttachmentsCount()
```


Obtiene recuento de archivos adjuntos

**Returns:**
int - recuento de archivos adjuntos
### getAttachmentsNames() {#getAttachmentsNames--}
```
public List<String> getAttachmentsNames()
```


Obtiene nombres de archivos adjuntos

**Returns:**
java.util.List<java.lang.String> - nombres de archivos adjuntos
