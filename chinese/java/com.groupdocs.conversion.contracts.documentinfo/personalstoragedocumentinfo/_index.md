---
title: "PersonalStorageDocumentInfo"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "包含个人存储文档元数据"
type: docs
weight: 29
url: /zh/java/com.groupdocs.conversion.contracts.documentinfo/personalstoragedocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class PersonalStorageDocumentInfo extends DocumentInfo
```

包含个人存储文档元数据

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PersonalStorageDocumentInfo(PersonalStorage storage, FileType format, long size)](#PersonalStorageDocumentInfo-com.aspose.email.PersonalStorage-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [isPasswordProtected()](#isPasswordProtected--) | 存储是否受密码保护 |
|
|  | [getRootFolderName()](#getRootFolderName--) | 根文件夹名称 |
|
|  | [getContentCount()](#getContentCount--) | 获取根文件夹中内容的计数 |
|
|  | [getFolders()](#getFolders--) | 存储中的文件夹 |
|
### PersonalStorageDocumentInfo(PersonalStorage storage, FileType format, long size) {#PersonalStorageDocumentInfo-com.aspose.email.PersonalStorage-com.groupdocs.conversion.filetypes.FileType-long-}
```
public PersonalStorageDocumentInfo(PersonalStorage storage, FileType format, long size)
```


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 存储 | com.aspose.email.PersonalStorage |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| 大小 | long |  |

### isPasswordProtected() {#isPasswordProtected--}
```
public boolean isPasswordProtected()
```


存储是否受密码保护


**Returns:**
布尔
### getRootFolderName() {#getRootFolderName--}
```
public String getRootFolderName()
```


根文件夹名称


**Returns:**
java.lang.String - 根文件夹名称

### getContentCount() {#getContentCount--}
```
public int getContentCount()
```


获取根文件夹中内容的计数


**Returns:**
int - 根文件夹中内容的计数

### getFolders() {#getFolders--}
```
public List<PersonalStorageFolderInfo> getFolders()
```


存储中的文件夹


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.documentinfo.PersonalStorageFolderInfo> - 存储中的文件夹

