---
title: "ProjectManagementDocumentInfo"
second_title: "Referencia de API de GroupDocs.Conversion for Java"
description: "Contiene metadatos del documento de gestión de proyectos"
type: docs
weight: 32
url: /es/java/com.groupdocs.conversion.contracts.documentinfo/projectmanagementdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class ProjectManagementDocumentInfo extends DocumentInfo
```

Contiene metadatos del documento de gestión de proyectos

## Constructores

| Constructor | Descripción |
| --- | --- |
| [ProjectManagementDocumentInfo(Project project, FileType format, long size)](#ProjectManagementDocumentInfo-com.aspose.tasks.Project-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getTasksCount()](#getTasksCount--) | Obtiene el recuento de tareas |
|
|  | [getStartDate()](#getStartDate--) | Obtiene la fecha de inicio del proyecto |
|
|  | [getEndDate()](#getEndDate--) | Obtiene la fecha de fin del proyecto |
|
### ProjectManagementDocumentInfo(Project project, FileType format, long size) {#ProjectManagementDocumentInfo-com.aspose.tasks.Project-com.groupdocs.conversion.filetypes.FileType-long-}
```
public ProjectManagementDocumentInfo(Project project, FileType format, long size)
```


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| proyecto | com.aspose.tasks.Project |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |

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


Obtiene la fecha de fin del proyecto


**Returns:**
java.util.Date - fecha de fin del proyecto

