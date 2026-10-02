---
title: "PersonalStorageDocumentInfo"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "يحتوي على بيانات تعريف مستند التخزين الشخصي"
type: docs
weight: 29
url: /ar/java/com.groupdocs.conversion.contracts.documentinfo/personalstoragedocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class PersonalStorageDocumentInfo extends DocumentInfo
```

يحتوي على بيانات تعريف مستند التخزين الشخصي

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [PersonalStorageDocumentInfo(PersonalStorage storage, FileType format, long size)](#PersonalStorageDocumentInfo-com.aspose.email.PersonalStorage-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [isPasswordProtected()](#isPasswordProtected--) | هل تم حماية التخزين بكلمة مرور |
|
|  | [getRootFolderName()](#getRootFolderName--) | اسم المجلد الجذر |
|
|  | [getContentCount()](#getContentCount--) | احصل على عدد المحتويات في المجلد الجذر |
|
|  | [getFolders()](#getFolders--) | المجلدات في التخزين |
|
### PersonalStorageDocumentInfo(PersonalStorage storage, FileType format, long size) {#PersonalStorageDocumentInfo-com.aspose.email.PersonalStorage-com.groupdocs.conversion.filetypes.FileType-long-}
```
public PersonalStorageDocumentInfo(PersonalStorage storage, FileType format, long size)
```


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| التخزين | com.aspose.email.PersonalStorage |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |

### isPasswordProtected() {#isPasswordProtected--}
```
public boolean isPasswordProtected()
```


هل تم حماية التخزين بكلمة مرور


**Returns:**
منطقي
### getRootFolderName() {#getRootFolderName--}
```
public String getRootFolderName()
```


اسم المجلد الجذر


**Returns:**
java.lang.String - اسم المجلد الجذر

### getContentCount() {#getContentCount--}
```
public int getContentCount()
```


احصل على عدد المحتويات في المجلد الجذر


**Returns:**
int - عدد المحتويات في المجلد الجذر

### getFolders() {#getFolders--}
```
public List<PersonalStorageFolderInfo> getFolders()
```


المجلدات في التخزين


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.documentinfo.PersonalStorageFolderInfo> - المجلدات في التخزين

