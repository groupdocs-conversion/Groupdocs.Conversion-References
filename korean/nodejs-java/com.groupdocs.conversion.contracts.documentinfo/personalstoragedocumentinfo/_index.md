---
title: "PersonalStorageDocumentInfo"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "개인 저장소 문서 메타데이터 포함"
type: docs
weight: 32
url: /ko/nodejs-java/com.groupdocs.conversion.contracts.documentinfo/personalstoragedocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class PersonalStorageDocumentInfo extends DocumentInfo
```

개인 저장소 문서 메타데이터 포함
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PersonalStorageDocumentInfo(PersonalStorage storage, FileType format, long size)](#PersonalStorageDocumentInfo-com.aspose.email.PersonalStorage-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [isPasswordProtected()](#isPasswordProtected--) | 스토리지는 비밀번호로 보호되어 있습니까 |
| [getRootFolderName()](#getRootFolderName--) | 루트 폴더 이름 |
| [getContentCount()](#getContentCount--) | 루트 폴더에 있는 항목 수를 가져옵니다 |
| [getFolders()](#getFolders--) | 스토리지의 폴더 |
### PersonalStorageDocumentInfo(PersonalStorage storage, FileType format, long size) {#PersonalStorageDocumentInfo-com.aspose.email.PersonalStorage-com.groupdocs.conversion.filetypes.FileType-long-}
```
public PersonalStorageDocumentInfo(PersonalStorage storage, FileType format, long size)
```


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 스토리지 | com.aspose.email.PersonalStorage |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| 크기 | long |  |

### isPasswordProtected() {#isPasswordProtected--}
```
public boolean isPasswordProtected()
```


스토리지는 비밀번호로 보호되어 있습니까

**Returns:**
boolean
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


루트 폴더에 있는 항목 수를 가져옵니다

**Returns:**
int - 루트 폴더에 있는 항목 수
### getFolders() {#getFolders--}
```
public List<PersonalStorageFolderInfo> getFolders()
```


스토리지의 폴더

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.documentinfo.PersonalStorageFolderInfo> - 스토리지의 폴더
