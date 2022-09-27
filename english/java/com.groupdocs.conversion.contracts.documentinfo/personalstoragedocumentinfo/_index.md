---
title: PersonalStorageDocumentInfo
second_title: GroupDocs.Conversion for Java API Reference
description: Contains personal storage document metadata
type: docs
weight: 30
url: /java/com.groupdocs.conversion.contracts.documentinfo/personalstoragedocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class PersonalStorageDocumentInfo extends DocumentInfo
```

Contains personal storage document metadata
## Constructors

| Constructor | Description |
| --- | --- |
| [PersonalStorageDocumentInfo(PersonalStorage storage, FileType format, long size)](#PersonalStorageDocumentInfo-com.aspose.email.PersonalStorage-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Methods

| Method | Description |
| --- | --- |
| [isPasswordProtected()](#isPasswordProtected--) | Is storage password protected |
| [getRootFolderName()](#getRootFolderName--) | Root folder name |
| [getContentCount()](#getContentCount--) | Get count of contents in the root folder |
| [getFolders()](#getFolders--) | Folders in the storage |
### PersonalStorageDocumentInfo(PersonalStorage storage, FileType format, long size) {#PersonalStorageDocumentInfo-com.aspose.email.PersonalStorage-com.groupdocs.conversion.filetypes.FileType-long-}
```
public PersonalStorageDocumentInfo(PersonalStorage storage, FileType format, long size)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| storage | com.aspose.email.PersonalStorage |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |

### isPasswordProtected() {#isPasswordProtected--}
```
public boolean isPasswordProtected()
```


Is storage password protected

**Returns:**
boolean
### getRootFolderName() {#getRootFolderName--}
```
public String getRootFolderName()
```


Root folder name

**Returns:**
java.lang.String - Root folder name
### getContentCount() {#getContentCount--}
```
public int getContentCount()
```


Get count of contents in the root folder

**Returns:**
int - count of contents in the root folder
### getFolders() {#getFolders--}
```
public List<String> getFolders()
```


Folders in the storage

**Returns:**
java.util.List<java.lang.String> - Folders in the storage
