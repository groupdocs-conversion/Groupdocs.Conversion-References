---
title: "ProjectManagementDocumentInfo"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "يحتوي على بيانات تعريف مستند إدارة المشروع"
type: docs
weight: 32
url: /ar/java/com.groupdocs.conversion.contracts.documentinfo/projectmanagementdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class ProjectManagementDocumentInfo extends DocumentInfo
```

يحتوي على بيانات تعريف مستند إدارة المشروع

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [ProjectManagementDocumentInfo(Project project, FileType format, long size)](#ProjectManagementDocumentInfo-com.aspose.tasks.Project-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getTasksCount()](#getTasksCount--) | يحصل على عدد المهام |
|
|  | [getStartDate()](#getStartDate--) | يحصل على تاريخ بدء المشروع |
|
|  | [getEndDate()](#getEndDate--) | يحصل على تاريخ انتهاء المشروع |
|
### ProjectManagementDocumentInfo(Project project, FileType format, long size) {#ProjectManagementDocumentInfo-com.aspose.tasks.Project-com.groupdocs.conversion.filetypes.FileType-long-}
```
public ProjectManagementDocumentInfo(Project project, FileType format, long size)
```


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| مشروع | com.aspose.tasks.Project |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |

### getTasksCount() {#getTasksCount--}
```
public int getTasksCount()
```


يحصل على عدد المهام


**Returns:**
int - عدد المهام

### getStartDate() {#getStartDate--}
```
public Date getStartDate()
```


يحصل على تاريخ بدء المشروع


**Returns:**
java.util.Date - تاريخ بدء المشروع

### getEndDate() {#getEndDate--}
```
public Date getEndDate()
```


يحصل على تاريخ انتهاء المشروع


**Returns:**
java.util.Date - تاريخ انتهاء المشروع

