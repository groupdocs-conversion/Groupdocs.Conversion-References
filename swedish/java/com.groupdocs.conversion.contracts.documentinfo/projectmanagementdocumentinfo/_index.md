---
title: "ProjectManagementDocumentInfo"
second_title: "GroupDocs.Conversion för Java API-referens"
description: "Innehåller metadata för ProjectManagement-dokument"
type: docs
weight: 32
url: /sv/java/com.groupdocs.conversion.contracts.documentinfo/projectmanagementdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class ProjectManagementDocumentInfo extends DocumentInfo
```

Innehåller metadata för ProjectManagement-dokument

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [ProjectManagementDocumentInfo(Project project, FileType format, long size)](#ProjectManagementDocumentInfo-com.aspose.tasks.Project-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getTasksCount()](#getTasksCount--) | Hämtar uppgiftsantal |
|
|  | [getStartDate()](#getStartDate--) | Hämtar projektets startdatum |
|
|  | [getEndDate()](#getEndDate--) | Hämtar projektets slutdatum |
|
### ProjectManagementDocumentInfo(Project project, FileType format, long size) {#ProjectManagementDocumentInfo-com.aspose.tasks.Project-com.groupdocs.conversion.filetypes.FileType-long-}
```
public ProjectManagementDocumentInfo(Project project, FileType format, long size)
```


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| projekt | com.aspose.tasks.Project |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| storlek | long |  |

### getTasksCount() {#getTasksCount--}
```
public int getTasksCount()
```


Hämtar uppgiftsantal


**Returns:**
int - uppgiftsantal

### getStartDate() {#getStartDate--}
```
public Date getStartDate()
```


Hämtar projektets startdatum


**Returns:**
java.util.Date - projektets startdatum

### getEndDate() {#getEndDate--}
```
public Date getEndDate()
```


Hämtar projektets slutdatum


**Returns:**
java.util.Date - projektets slutdatum

