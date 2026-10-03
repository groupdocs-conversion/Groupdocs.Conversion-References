---
title: "PersonalStorageDocumentInfo"
second_title: "Справочник API GroupDocs.Conversion for Java"
description: "Содержит метаданные документа личного хранилища"
type: docs
weight: 29
url: /ru/java/com.groupdocs.conversion.contracts.documentinfo/personalstoragedocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class PersonalStorageDocumentInfo extends DocumentInfo
```

Содержит метаданные документа личного хранилища

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PersonalStorageDocumentInfo(PersonalStorage storage, FileType format, long size)](#PersonalStorageDocumentInfo-com.aspose.email.PersonalStorage-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [isPasswordProtected()](#isPasswordProtected--) | Защищено ли хранилище паролем |
|
|  | [getRootFolderName()](#getRootFolderName--) | Имя корневой папки |
|
|  | [getContentCount()](#getContentCount--) | Получить количество элементов в корневой папке |
|
|  | [getFolders()](#getFolders--) | Папки в хранилище |
|
### PersonalStorageDocumentInfo(PersonalStorage storage, FileType format, long size) {#PersonalStorageDocumentInfo-com.aspose.email.PersonalStorage-com.groupdocs.conversion.filetypes.FileType-long-}
```
public PersonalStorageDocumentInfo(PersonalStorage storage, FileType format, long size)
```


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| хранилище | com.aspose.email.PersonalStorage |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |

### isPasswordProtected() {#isPasswordProtected--}
```
public boolean isPasswordProtected()
```


Защищено ли хранилище паролем


**Returns:**
логический
### getRootFolderName() {#getRootFolderName--}
```
public String getRootFolderName()
```


Имя корневой папки


**Returns:**
java.lang.String - Имя корневой папки

### getContentCount() {#getContentCount--}
```
public int getContentCount()
```


Получить количество элементов в корневой папке


**Returns:**
int - количество элементов в корневой папке

### getFolders() {#getFolders--}
```
public List<PersonalStorageFolderInfo> getFolders()
```


Папки в хранилище


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.documentinfo.PersonalStorageFolderInfo> - Папки в хранилище

