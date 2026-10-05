---
title: "ProjectManagementDocumentInfo"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Содержит метаданные документа ProjectManagement"
type: docs
weight: 35
url: /ru/nodejs-java/com.groupdocs.conversion.contracts.documentinfo/projectmanagementdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class ProjectManagementDocumentInfo extends DocumentInfo
```

Содержит метаданные документа ProjectManagement
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ProjectManagementDocumentInfo(Project project, FileType format, long size)](#ProjectManagementDocumentInfo-com.aspose.tasks.Project-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getTasksCount()](#getTasksCount--) | Получает количество задач |
| [getStartDate()](#getStartDate--) | Получает дату начала проекта |
| [getEndDate()](#getEndDate--) | Получает дату окончания проекта |
### ProjectManagementDocumentInfo(Project project, FileType format, long size) {#ProjectManagementDocumentInfo-com.aspose.tasks.Project-com.groupdocs.conversion.filetypes.FileType-long-}
```
public ProjectManagementDocumentInfo(Project project, FileType format, long size)
```


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| проект | com.aspose.tasks.Project |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| размер | long |  |

### getTasksCount() {#getTasksCount--}
```
public int getTasksCount()
```


Получает количество задач

**Returns:**
int - количество задач
### getStartDate() {#getStartDate--}
```
public Date getStartDate()
```


Получает дату начала проекта

**Returns:**
java.util.Date - дата начала проекта
### getEndDate() {#getEndDate--}
```
public Date getEndDate()
```


Получает дату окончания проекта

**Returns:**
java.util.Date - дата окончания проекта
