---
title: "PersonalStorageDocumentInfo"
second_title: "Node.js için GroupDocs.Conversion, Java üzerinden API Referansı"
description: "Kişisel depolama belge meta verilerini içerir"
type: docs
weight: 32
url: /tr/nodejs-java/com.groupdocs.conversion.contracts.documentinfo/personalstoragedocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class PersonalStorageDocumentInfo extends DocumentInfo
```

Kişisel depolama belge meta verilerini içerir
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PersonalStorageDocumentInfo(PersonalStorage storage, FileType format, long size)](#PersonalStorageDocumentInfo-com.aspose.email.PersonalStorage-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [isPasswordProtected()](#isPasswordProtected--) | Depolama şifre korumalı mı |
| [getRootFolderName()](#getRootFolderName--) | Kök klasör adı |
| [getContentCount()](#getContentCount--) | Kök klasördeki içerik sayısını al |
| [getFolders()](#getFolders--) | Depodaki klasörler |
### PersonalStorageDocumentInfo(PersonalStorage storage, FileType format, long size) {#PersonalStorageDocumentInfo-com.aspose.email.PersonalStorage-com.groupdocs.conversion.filetypes.FileType-long-}
```
public PersonalStorageDocumentInfo(PersonalStorage storage, FileType format, long size)
```


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| depo | com.aspose.email.PersonalStorage |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |

### isPasswordProtected() {#isPasswordProtected--}
```
public boolean isPasswordProtected()
```


Depolama şifre korumalı mı

**Returns:**
boolean
### getRootFolderName() {#getRootFolderName--}
```
public String getRootFolderName()
```


Kök klasör adı

**Returns:**
java.lang.String - Kök klasör adı
### getContentCount() {#getContentCount--}
```
public int getContentCount()
```


Kök klasördeki içerik sayısını al

**Returns:**
int - kök klasördeki içerik sayısı
### getFolders() {#getFolders--}
```
public List<PersonalStorageFolderInfo> getFolders()
```


Depodaki klasörler

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.documentinfo.PersonalStorageFolderInfo> - Depodaki klasörler
