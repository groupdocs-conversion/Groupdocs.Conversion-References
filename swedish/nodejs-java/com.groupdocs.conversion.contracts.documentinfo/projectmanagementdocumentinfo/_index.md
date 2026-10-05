---
title: "ProjectManagementDocumentInfo"
second_title: "GroupDocs.Conversion för Node.js via Java API-referens"
description: "Innehåller ProjectManagement-dokumentmetadata"
type: docs
weight: 35
url: /sv/nodejs-java/com.groupdocs.conversion.contracts.documentinfo/projectmanagementdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class ProjectManagementDocumentInfo extends DocumentInfo
```

Innehåller ProjectManagement-dokumentmetadata
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [ProjectManagementDocumentInfo(Project project, FileType format, long size)](#ProjectManagementDocumentInfo-com.aspose.tasks.Project-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getTasksCount()](#getTasksCount--) | Hämtar antal uppgifter |
| [getStartDate()](#getStartDate--) | Hämtar Project startdatum |
| [getEndDate()](#getEndDate--) | Hämtar Project slutdatum |
### ProjectManagementDocumentInfo(Project project, FileType format, long size) {#ProjectManagementDocumentInfo-com.aspose.tasks.Project-com.groupdocs.conversion.filetypes.FileType-long-}
```
public ProjectManagementDocumentInfo(Project project, FileType format, long size)
```


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| projekt | com.aspose.tasks.Project |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |

### getTasksCount() {#getTasksCount--}
```
public int getTasksCount()
```


Hämtar antal uppgifter

**Returns:**
int - uppgiftsantal
### getStartDate() {#getStartDate--}
```
public Date getStartDate()
```


Hämtar Project startdatum

**Returns:**
java.util.Date - Projektets startdatum
### getEndDate() {#getEndDate--}
```
public Date getEndDate()
```


Hämtar Project slutdatum

**Returns:**
java.util.Date - Projektets slutdatum
