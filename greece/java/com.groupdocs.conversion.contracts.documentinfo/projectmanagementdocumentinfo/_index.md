---
title: "ProjectManagementDocumentInfo"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Περιέχει μεταδεδομένα εγγράφου διαχείρισης έργου"
type: docs
weight: 32
url: /el/java/com.groupdocs.conversion.contracts.documentinfo/projectmanagementdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class ProjectManagementDocumentInfo extends DocumentInfo
```

Περιέχει μεταδεδομένα εγγράφου διαχείρισης έργου

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [ProjectManagementDocumentInfo(Project project, FileType format, long size)](#ProjectManagementDocumentInfo-com.aspose.tasks.Project-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getTasksCount()](#getTasksCount--) | Λαμβάνει αριθμό εργασιών |
|
|  | [getStartDate()](#getStartDate--) | Λαμβάνει ημερομηνία έναρξης έργου |
|
|  | [getEndDate()](#getEndDate--) | Λαμβάνει ημερομηνία λήξης έργου |
|
### ProjectManagementDocumentInfo(Project project, FileType format, long size) {#ProjectManagementDocumentInfo-com.aspose.tasks.Project-com.groupdocs.conversion.filetypes.FileType-long-}
```
public ProjectManagementDocumentInfo(Project project, FileType format, long size)
```


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| έργο | com.aspose.tasks.Project |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| μέγεθος | long |  |

### getTasksCount() {#getTasksCount--}
```
public int getTasksCount()
```


Λαμβάνει αριθμό εργασιών


**Returns:**
int - αριθμός εργασιών

### getStartDate() {#getStartDate--}
```
public Date getStartDate()
```


Λαμβάνει ημερομηνία έναρξης έργου


**Returns:**
java.util.Date - ημερομηνία έναρξης έργου

### getEndDate() {#getEndDate--}
```
public Date getEndDate()
```


Λαμβάνει ημερομηνία λήξης έργου


**Returns:**
java.util.Date - ημερομηνία λήξης έργου

