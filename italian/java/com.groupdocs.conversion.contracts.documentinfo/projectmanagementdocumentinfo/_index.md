---
title: "ProjectManagementDocumentInfo"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Contiene i metadati del documento ProjectManagement"
type: docs
weight: 32
url: /it/java/com.groupdocs.conversion.contracts.documentinfo/projectmanagementdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class ProjectManagementDocumentInfo extends DocumentInfo
```

Contiene i metadati del documento ProjectManagement

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ProjectManagementDocumentInfo(Project project, FileType format, long size)](#ProjectManagementDocumentInfo-com.aspose.tasks.Project-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getTasksCount()](#getTasksCount--) | Ottiene il conteggio delle attività |
|
|  | [getStartDate()](#getStartDate--) | Ottiene la data di inizio del progetto |
|
|  | [getEndDate()](#getEndDate--) | Ottiene la data di fine del progetto |
|
### ProjectManagementDocumentInfo(Project project, FileType format, long size) {#ProjectManagementDocumentInfo-com.aspose.tasks.Project-com.groupdocs.conversion.filetypes.FileType-long-}
```
public ProjectManagementDocumentInfo(Project project, FileType format, long size)
```


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| progetto | com.aspose.tasks.Project |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| dimensione | long |  |

### getTasksCount() {#getTasksCount--}
```
public int getTasksCount()
```


Ottiene il conteggio delle attività


**Returns:**
int - conteggio delle attività

### getStartDate() {#getStartDate--}
```
public Date getStartDate()
```


Ottiene la data di inizio del progetto


**Returns:**
java.util.Date - data di inizio del progetto

### getEndDate() {#getEndDate--}
```
public Date getEndDate()
```


Ottiene la data di fine del progetto


**Returns:**
java.util.Date - data di fine del progetto

