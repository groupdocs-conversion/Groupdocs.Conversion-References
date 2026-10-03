---
title: "ProjectManagementDocumentInfo"
second_title: "GroupDocs.Conversion voor Java API-referentie"
description: "Bevat metadata van ProjectManagement-document"
type: docs
weight: 32
url: /nl/java/com.groupdocs.conversion.contracts.documentinfo/projectmanagementdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class ProjectManagementDocumentInfo extends DocumentInfo
```

Bevat metadata van ProjectManagement-document

## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [ProjectManagementDocumentInfo(Project project, FileType format, long size)](#ProjectManagementDocumentInfo-com.aspose.tasks.Project-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getTasksCount()](#getTasksCount--) | Haalt het aantal taken op |
|
|  | [getStartDate()](#getStartDate--) | Haalt de startdatum van het project op |
|
|  | [getEndDate()](#getEndDate--) | Haalt de einddatum van het project op |
|
### ProjectManagementDocumentInfo(Project project, FileType format, long size) {#ProjectManagementDocumentInfo-com.aspose.tasks.Project-com.groupdocs.conversion.filetypes.FileType-long-}
```
public ProjectManagementDocumentInfo(Project project, FileType format, long size)
```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| project | com.aspose.tasks.Project |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |

### getTasksCount() {#getTasksCount--}
```
public int getTasksCount()
```


Haalt het aantal taken op


**Returns:**
int - taak aantal

### getStartDate() {#getStartDate--}
```
public Date getStartDate()
```


Haalt de startdatum van het project op


**Returns:**
java.util.Date - project startdatum

### getEndDate() {#getEndDate--}
```
public Date getEndDate()
```


Haalt de einddatum van het project op


**Returns:**
java.util.Date - project einddatum

