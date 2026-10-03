---
title: "PersonalStorageDocumentInfo"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Berisi metadata dokumen penyimpanan pribadi"
type: docs
weight: 29
url: /id/java/com.groupdocs.conversion.contracts.documentinfo/personalstoragedocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class PersonalStorageDocumentInfo extends DocumentInfo
```

Berisi metadata dokumen penyimpanan pribadi

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PersonalStorageDocumentInfo(PersonalStorage storage, FileType format, long size)](#PersonalStorageDocumentInfo-com.aspose.email.PersonalStorage-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [isPasswordProtected()](#isPasswordProtected--) | Apakah storage dilindungi kata sandi |
|
|  | [getRootFolderName()](#getRootFolderName--) | Nama folder root |
|
|  | [getContentCount()](#getContentCount--) | Dapatkan jumlah konten di folder root |
|
|  | [getFolders()](#getFolders--) | Folder di storage |
|
### PersonalStorageDocumentInfo(PersonalStorage storage, FileType format, long size) {#PersonalStorageDocumentInfo-com.aspose.email.PersonalStorage-com.groupdocs.conversion.filetypes.FileType-long-}
```
public PersonalStorageDocumentInfo(PersonalStorage storage, FileType format, long size)
```


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| storage | com.aspose.email.PersonalStorage |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |

### isPasswordProtected() {#isPasswordProtected--}
```
public boolean isPasswordProtected()
```


Apakah storage dilindungi kata sandi


**Returns:**
boolean
### getRootFolderName() {#getRootFolderName--}
```
public String getRootFolderName()
```


Nama folder root


**Returns:**
java.lang.String - Nama folder root

### getContentCount() {#getContentCount--}
```
public int getContentCount()
```


Dapatkan jumlah konten di folder root


**Returns:**
int - jumlah konten di folder root

### getFolders() {#getFolders--}
```
public List<PersonalStorageFolderInfo> getFolders()
```


Folder di storage


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.documentinfo.PersonalStorageFolderInfo> - Folder di storage

