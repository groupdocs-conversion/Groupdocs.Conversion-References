---
title: "EmailDocumentInfo"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Contient les métadonnées du document Email"
type: docs
weight: 17
url: /fr/java/com.groupdocs.conversion.contracts.documentinfo/emaildocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class EmailDocumentInfo extends DocumentInfo
```

Contient les métadonnées du document Email

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmailDocumentInfo(MailMessage mail, FileType format, long size)](#EmailDocumentInfo-com.aspose.email.MailMessage-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [isSigned()](#isSigned--) | Obtient s'il est signé |
|
|  | [isEncrypted()](#isEncrypted--) | Obtient est chiffré |
|
|  | [isHtml()](#isHtml--) | Obtient s'il est HTML |
|
|  | [getAttachmentsCount()](#getAttachmentsCount--) | Obtient le nombre de pièces jointes |
|
|  | [getAttachmentsNames()](#getAttachmentsNames--) | Obtient les noms des pièces jointes |
|
### EmailDocumentInfo(MailMessage mail, FileType format, long size) {#EmailDocumentInfo-com.aspose.email.MailMessage-com.groupdocs.conversion.filetypes.FileType-long-}
```
public EmailDocumentInfo(MailMessage mail, FileType format, long size)
```


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| courriel | com.aspose.email.MailMessage |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |

### isSigned() {#isSigned--}
```
public boolean isSigned()
```


Obtient s'il est signé


**Returns:**
booléen - vrai si signé

### isEncrypted() {#isEncrypted--}
```
public boolean isEncrypted()
```


Obtient est chiffré


**Returns:**
booléen - vrai si chiffré

### isHtml() {#isHtml--}
```
public boolean isHtml()
```


Obtient s'il est HTML


**Returns:**
booléen - vrai si HTML

### getAttachmentsCount() {#getAttachmentsCount--}
```
public int getAttachmentsCount()
```


Obtient le nombre de pièces jointes


**Returns:**
int - nombre de pièces jointes

### getAttachmentsNames() {#getAttachmentsNames--}
```
public List<String> getAttachmentsNames()
```


Obtient les noms des pièces jointes


**Returns:**
java.util.List<java.lang.String> - noms des pièces jointes

