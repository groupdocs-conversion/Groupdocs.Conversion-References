---
title: "ProjectManagementDocumentInfo"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Contient les métadonnées du document ProjectManagement"
type: docs
weight: 32
url: /fr/java/com.groupdocs.conversion.contracts.documentinfo/projectmanagementdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class ProjectManagementDocumentInfo extends DocumentInfo
```

Contient les métadonnées du document ProjectManagement

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ProjectManagementDocumentInfo(Project project, FileType format, long size)](#ProjectManagementDocumentInfo-com.aspose.tasks.Project-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getTasksCount()](#getTasksCount--) | Obtient le nombre de tâches |
|
|  | [getStartDate()](#getStartDate--) | Obtient la date de début du projet |
|
|  | [getEndDate()](#getEndDate--) | Obtient la date de fin du projet |
|
### ProjectManagementDocumentInfo(Project project, FileType format, long size) {#ProjectManagementDocumentInfo-com.aspose.tasks.Project-com.groupdocs.conversion.filetypes.FileType-long-}
```
public ProjectManagementDocumentInfo(Project project, FileType format, long size)
```


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| projet | com.aspose.tasks.Project |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |

### getTasksCount() {#getTasksCount--}
```
public int getTasksCount()
```


Obtient le nombre de tâches


**Returns:**
int - nombre de tâches

### getStartDate() {#getStartDate--}
```
public Date getStartDate()
```


Obtient la date de début du projet


**Returns:**
java.util.Date - date de début du projet

### getEndDate() {#getEndDate--}
```
public Date getEndDate()
```


Obtient la date de fin du projet


**Returns:**
java.util.Date - date de fin du projet

