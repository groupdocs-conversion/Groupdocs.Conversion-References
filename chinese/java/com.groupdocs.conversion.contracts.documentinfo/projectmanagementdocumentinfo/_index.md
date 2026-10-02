---
title: "ProjectManagementDocumentInfo"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "包含项目管理文档元数据"
type: docs
weight: 32
url: /zh/java/com.groupdocs.conversion.contracts.documentinfo/projectmanagementdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class ProjectManagementDocumentInfo extends DocumentInfo
```

包含项目管理文档元数据

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ProjectManagementDocumentInfo(Project project, FileType format, long size)](#ProjectManagementDocumentInfo-com.aspose.tasks.Project-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getTasksCount()](#getTasksCount--) | 获取任务计数 |
|
|  | [getStartDate()](#getStartDate--) | 获取项目开始日期 |
|
|  | [getEndDate()](#getEndDate--) | 获取项目结束日期 |
|
### ProjectManagementDocumentInfo(Project project, FileType format, long size) {#ProjectManagementDocumentInfo-com.aspose.tasks.Project-com.groupdocs.conversion.filetypes.FileType-long-}
```
public ProjectManagementDocumentInfo(Project project, FileType format, long size)
```


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 项目 | com.aspose.tasks.Project |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| 大小 | long |  |

### getTasksCount() {#getTasksCount--}
```
public int getTasksCount()
```


获取任务计数


**Returns:**
int - 任务计数

### getStartDate() {#getStartDate--}
```
public Date getStartDate()
```


获取项目开始日期


**Returns:**
java.util.Date - 项目开始日期

### getEndDate() {#getEndDate--}
```
public Date getEndDate()
```


获取项目结束日期


**Returns:**
java.util.Date - 项目结束日期

