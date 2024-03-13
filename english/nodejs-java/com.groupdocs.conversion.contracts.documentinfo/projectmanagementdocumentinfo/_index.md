---
title: ProjectManagementDocumentInfo
second_title: GroupDocs.Conversion for Node.js via Java API Reference
description: Contains ProjectManagement document metadata
type: docs
weight: 35
url: /nodejs-java/com.groupdocs.conversion.contracts.documentinfo/projectmanagementdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class ProjectManagementDocumentInfo extends DocumentInfo
```

Contains ProjectManagement document metadata
## Constructors

| Constructor | Description |
| --- | --- |
| [ProjectManagementDocumentInfo(Project project, FileType format, long size)](#ProjectManagementDocumentInfo-com.aspose.tasks.Project-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Methods

| Method | Description |
| --- | --- |
| [getTasksCount()](#getTasksCount--) | Gets task count |
| [getStartDate()](#getStartDate--) | Gets Project start date |
| [getEndDate()](#getEndDate--) | Gets Project end date |
### ProjectManagementDocumentInfo(Project project, FileType format, long size) {#ProjectManagementDocumentInfo-com.aspose.tasks.Project-com.groupdocs.conversion.filetypes.FileType-long-}
```
public ProjectManagementDocumentInfo(Project project, FileType format, long size)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| project | com.aspose.tasks.Project |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |

### getTasksCount() {#getTasksCount--}
```
public int getTasksCount()
```


Gets task count

**Returns:**
int - task count
### getStartDate() {#getStartDate--}
```
public Date getStartDate()
```


Gets Project start date

**Returns:**
java.util.Date - Project start date
### getEndDate() {#getEndDate--}
```
public Date getEndDate()
```


Gets Project end date

**Returns:**
java.util.Date - Project end date
