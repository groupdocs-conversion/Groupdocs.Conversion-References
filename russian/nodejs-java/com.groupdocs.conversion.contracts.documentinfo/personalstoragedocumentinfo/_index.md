---
title: "PersonalStorageDocumentInfo"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Содержит метаданные документа personal storage"
type: docs
weight: 32
url: /ru/nodejs-java/com.groupdocs.conversion.contracts.documentinfo/personalstoragedocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class PersonalStorageDocumentInfo extends DocumentInfo
```

Содержит метаданные документа personal storage
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PersonalStorageDocumentInfo(PersonalStorage storage, FileType format, long size)](#PersonalStorageDocumentInfo-com.aspose.email.PersonalStorage-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [isPasswordProtected()](#isPasswordProtected--) | Защищён ли пароль хранилища |
| [getRootFolderName()](#getRootFolderName--) | Имя корневой папки |
| [getContentCount()](#getContentCount--) | Получить количество содержимого в корневой папке |
| [getFolders()](#getFolders--) | Папки в хранилище |
### PersonalStorageDocumentInfo(PersonalStorage storage, FileType format, long size) {#PersonalStorageDocumentInfo-com.aspose.email.PersonalStorage-com.groupdocs.conversion.filetypes.FileType-long-}
```
public PersonalStorageDocumentInfo(PersonalStorage storage, FileType format, long size)
```


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| хранилище | com.aspose.email.PersonalStorage |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| размер | long |  |

### isPasswordProtected() {#isPasswordProtected--}
```
public boolean isPasswordProtected()
```


Защищён ли пароль хранилища

**Returns:**
boolean
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


Получить количество содержимого в корневой папке

**Returns:**
int - количество содержимого в корневой папке
### getFolders() {#getFolders--}
```
public List<PersonalStorageFolderInfo> getFolders()
```


Папки в хранилище

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.documentinfo.PersonalStorageFolderInfo> - Папки в хранилище
