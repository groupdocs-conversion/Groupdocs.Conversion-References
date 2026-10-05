---
title: "ProjectManagementDocumentInfo"
second_title: "Referencia de API de GroupDocs.Conversion para Node.js vía Java"
description: "Contiene metadatos del documento ProjectManagement"
type: docs
weight: 35
url: /es/nodejs-java/com.groupdocs.conversion.contracts.documentinfo/projectmanagementdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class ProjectManagementDocumentInfo extends DocumentInfo
```

Contiene metadatos del documento ProjectManagement
## Constructores

| Constructor | Descripción |
| --- | --- |
| [ProjectManagementDocumentInfo(Project project, FileType format, long size)](#ProjectManagementDocumentInfo-com.aspose.tasks.Project-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getTasksCount()](#getTasksCount--) | Obtiene el recuento de tareas |
| [getStartDate()](#getStartDate--) | Obtiene la fecha de inicio del proyecto |
| [getEndDate()](#getEndDate--) | Obtiene la fecha de finalización del proyecto |
### ProjectManagementDocumentInfo(Project project, FileType format, long size) {#ProjectManagementDocumentInfo-com.aspose.tasks.Project-com.groupdocs.conversion.filetypes.FileType-long-}
```
public ProjectManagementDocumentInfo(Project project, FileType format, long size)
```


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| proyecto | com.aspose.tasks.Project |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| tamaño | long |  |

### getTasksCount() {#getTasksCount--}
```
public int getTasksCount()
```


Obtiene el recuento de tareas

**Returns:**
int - recuento de tareas
### getStartDate() {#getStartDate--}
```
public Date getStartDate()
```


Obtiene la fecha de inicio del proyecto

**Returns:**
java.util.Date - fecha de inicio del proyecto
### getEndDate() {#getEndDate--}
```
public Date getEndDate()
```


Obtiene la fecha de finalización del proyecto

**Returns:**
java.util.Date - fecha de finalización del proyecto
