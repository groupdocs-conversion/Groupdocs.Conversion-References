---
title: "ProjectManagementDocumentInfo"
second_title: "GroupDocs.Conversion for Java API 레퍼런스"
description: "ProjectManagement 문서 메타데이터를 포함합니다"
type: docs
weight: 32
url: /ko/java/com.groupdocs.conversion.contracts.documentinfo/projectmanagementdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class ProjectManagementDocumentInfo extends DocumentInfo
```

ProjectManagement 문서 메타데이터를 포함합니다

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [ProjectManagementDocumentInfo(Project project, FileType format, long size)](#ProjectManagementDocumentInfo-com.aspose.tasks.Project-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getTasksCount()](#getTasksCount--) | 작업 수를 가져옵니다 |
|
|  | [getStartDate()](#getStartDate--) | 프로젝트 시작 날짜를 가져옵니다 |
|
|  | [getEndDate()](#getEndDate--) | 프로젝트 종료 날짜를 가져옵니다 |
|
### ProjectManagementDocumentInfo(Project project, FileType format, long size) {#ProjectManagementDocumentInfo-com.aspose.tasks.Project-com.groupdocs.conversion.filetypes.FileType-long-}
```
public ProjectManagementDocumentInfo(Project project, FileType format, long size)
```


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 프로젝트 | com.aspose.tasks.Project |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |

### getTasksCount() {#getTasksCount--}
```
public int getTasksCount()
```


작업 수를 가져옵니다


**Returns:**
int - 작업 수

### getStartDate() {#getStartDate--}
```
public Date getStartDate()
```


프로젝트 시작 날짜를 가져옵니다


**Returns:**
java.util.Date - 프로젝트 시작 날짜

### getEndDate() {#getEndDate--}
```
public Date getEndDate()
```


프로젝트 종료 날짜를 가져옵니다


**Returns:**
java.util.Date - 프로젝트 종료 날짜

