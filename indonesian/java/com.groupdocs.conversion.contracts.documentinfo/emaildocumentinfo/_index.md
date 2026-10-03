---
title: "EmailDocumentInfo"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Berisi metadata dokumen Email"
type: docs
weight: 17
url: /id/java/com.groupdocs.conversion.contracts.documentinfo/emaildocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class EmailDocumentInfo extends DocumentInfo
```

Berisi metadata dokumen Email

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [EmailDocumentInfo(MailMessage mail, FileType format, long size)](#EmailDocumentInfo-com.aspose.email.MailMessage-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [isSigned()](#isSigned--) | Mendapatkan apakah ditandatangani |
|
|  | [isEncrypted()](#isEncrypted--) | Mendapatkan apakah terenkripsi |
|
|  | [isHtml()](#isHtml--) | Mendapatkan apakah HTML |
|
|  | [getAttachmentsCount()](#getAttachmentsCount--) | Mendapatkan jumlah lampiran |
|
|  | [getAttachmentsNames()](#getAttachmentsNames--) | Mendapatkan nama lampiran |
|
### EmailDocumentInfo(MailMessage mail, FileType format, long size) {#EmailDocumentInfo-com.aspose.email.MailMessage-com.groupdocs.conversion.filetypes.FileType-long-}
```
public EmailDocumentInfo(MailMessage mail, FileType format, long size)
```


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| surat | com.aspose.email.MailMessage |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |

### isSigned() {#isSigned--}
```
public boolean isSigned()
```


Mendapatkan apakah ditandatangani


**Returns:**
boolean - true jika ditandatangani

### isEncrypted() {#isEncrypted--}
```
public boolean isEncrypted()
```


Mendapatkan apakah terenkripsi


**Returns:**
boolean - true jika dienkripsi

### isHtml() {#isHtml--}
```
public boolean isHtml()
```


Mendapatkan apakah HTML


**Returns:**
boolean - true jika HTML

### getAttachmentsCount() {#getAttachmentsCount--}
```
public int getAttachmentsCount()
```


Mendapatkan jumlah lampiran


**Returns:**
int - jumlah lampiran

### getAttachmentsNames() {#getAttachmentsNames--}
```
public List<String> getAttachmentsNames()
```


Mendapatkan nama lampiran


**Returns:**
java.util.List<java.lang.String> - nama lampiran

