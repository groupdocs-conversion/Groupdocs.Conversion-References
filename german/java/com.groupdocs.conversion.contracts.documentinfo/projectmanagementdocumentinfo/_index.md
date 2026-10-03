---
title: "ProjectManagementDocumentInfo"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Enthält Metadaten des ProjectManagement-Dokuments"
type: docs
weight: 32
url: /de/java/com.groupdocs.conversion.contracts.documentinfo/projectmanagementdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class ProjectManagementDocumentInfo extends DocumentInfo
```

Enthält Metadaten des ProjectManagement-Dokuments

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ProjectManagementDocumentInfo(Project project, FileType format, long size)](#ProjectManagementDocumentInfo-com.aspose.tasks.Project-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getTasksCount()](#getTasksCount--) | Ermittelt die Aufgabenanzahl |
|
|  | [getStartDate()](#getStartDate--) | Ermittelt das Projektstartdatum |
|
|  | [getEndDate()](#getEndDate--) | Ermittelt das Projektenddatum |
|
### ProjectManagementDocumentInfo(Project project, FileType format, long size) {#ProjectManagementDocumentInfo-com.aspose.tasks.Project-com.groupdocs.conversion.filetypes.FileType-long-}
```
public ProjectManagementDocumentInfo(Project project, FileType format, long size)
```


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Projekt | com.aspose.tasks.Project |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| Größe | long |  |

### getTasksCount() {#getTasksCount--}
```
public int getTasksCount()
```


Ermittelt die Aufgabenanzahl


**Returns:**
int - Aufgabenanzahl

### getStartDate() {#getStartDate--}
```
public Date getStartDate()
```


Ermittelt das Projektstartdatum


**Returns:**
java.util.Date - Projektstartdatum

### getEndDate() {#getEndDate--}
```
public Date getEndDate()
```


Ermittelt das Projektenddatum


**Returns:**
java.util.Date - Projektenddatum

