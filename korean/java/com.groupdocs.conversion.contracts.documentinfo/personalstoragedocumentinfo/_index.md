---
title: "PersonalStorageDocumentInfo"
second_title: "GroupDocs.Conversion for Java API 레퍼런스"
description: "personal storage 문서 메타데이터를 포함합니다"
type: docs
weight: 29
url: /ko/java/com.groupdocs.conversion.contracts.documentinfo/personalstoragedocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class PersonalStorageDocumentInfo extends DocumentInfo
```

personal storage 문서 메타데이터를 포함합니다

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PersonalStorageDocumentInfo(PersonalStorage storage, FileType format, long size)](#PersonalStorageDocumentInfo-com.aspose.email.PersonalStorage-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [isPasswordProtected()](#isPasswordProtected--) | 스토리지가 비밀번호로 보호되는지 여부 |
|
|  | [getRootFolderName()](#getRootFolderName--) | 루트 폴더 이름 |
|
|  | [getContentCount()](#getContentCount--) | 루트 폴더에 있는 내용 수 가져오기 |
|
|  | [getFolders()](#getFolders--) | 스토리지에 있는 폴더 |
|
### PersonalStorageDocumentInfo(PersonalStorage storage, FileType format, long size) {#PersonalStorageDocumentInfo-com.aspose.email.PersonalStorage-com.groupdocs.conversion.filetypes.FileType-long-}
```
public PersonalStorageDocumentInfo(PersonalStorage storage, FileType format, long size)
```


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 스토리지 | com.aspose.email.PersonalStorage |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |

### isPasswordProtected() {#isPasswordProtected--}
```
public boolean isPasswordProtected()
```


스토리지가 비밀번호로 보호되는지 여부


**Returns:**
불리언
### getRootFolderName() {#getRootFolderName--}
```
public String getRootFolderName()
```


루트 폴더 이름


**Returns:**
java.lang.String - 루트 폴더 이름

### getContentCount() {#getContentCount--}
```
public int getContentCount()
```


루트 폴더에 있는 내용 수 가져오기


**Returns:**
int - 루트 폴더에 있는 내용 수

### getFolders() {#getFolders--}
```
public List<PersonalStorageFolderInfo> getFolders()
```


스토리지에 있는 폴더


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.documentinfo.PersonalStorageFolderInfo> - 스토리지에 있는 폴더

