---
title: "ProjectManagementDocumentInfo"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "ProjectManagement 문서 메타데이터 포함"
type: docs
weight: 35
url: /ko/nodejs-java/com.groupdocs.conversion.contracts.documentinfo/projectmanagementdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class ProjectManagementDocumentInfo extends DocumentInfo
```

ProjectManagement 문서 메타데이터 포함
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [ProjectManagementDocumentInfo(Project project, FileType format, long size)](#ProjectManagementDocumentInfo-com.aspose.tasks.Project-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getTasksCount()](#getTasksCount--) | 작업 수를 가져옵니다 |
| [getStartDate()](#getStartDate--) | Project 시작 날짜를 가져옵니다 |
| [getEndDate()](#getEndDate--) | Project 종료 날짜를 가져옵니다 |
### ProjectManagementDocumentInfo(Project project, FileType format, long size) {#ProjectManagementDocumentInfo-com.aspose.tasks.Project-com.groupdocs.conversion.filetypes.FileType-long-}
```
public ProjectManagementDocumentInfo(Project project, FileType format, long size)
```


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 프로젝트 | com.aspose.tasks.Project |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| 크기 | long |  |

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


Project 시작 날짜를 가져옵니다

**Returns:**
java.util.Date - Project 시작 날짜
### getEndDate() {#getEndDate--}
```
public Date getEndDate()
```


Project 종료 날짜를 가져옵니다

**Returns:**
java.util.Date - Project 종료 날짜
