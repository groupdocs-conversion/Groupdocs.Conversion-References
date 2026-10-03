---
title: "ProjectManagementDocumentInfo"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Berisi metadata dokumen Manajemen Proyek"
type: docs
weight: 32
url: /id/java/com.groupdocs.conversion.contracts.documentinfo/projectmanagementdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class ProjectManagementDocumentInfo extends DocumentInfo
```

Berisi metadata dokumen Manajemen Proyek

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ProjectManagementDocumentInfo(Project project, FileType format, long size)](#ProjectManagementDocumentInfo-com.aspose.tasks.Project-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getTasksCount()](#getTasksCount--) | Mendapatkan jumlah tugas |
|
|  | [getStartDate()](#getStartDate--) | Mendapatkan tanggal mulai Proyek |
|
|  | [getEndDate()](#getEndDate--) | Mendapatkan tanggal selesai Proyek |
|
### ProjectManagementDocumentInfo(Project project, FileType format, long size) {#ProjectManagementDocumentInfo-com.aspose.tasks.Project-com.groupdocs.conversion.filetypes.FileType-long-}
```
public ProjectManagementDocumentInfo(Project project, FileType format, long size)
```


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| proyek | com.aspose.tasks.Project |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |

### getTasksCount() {#getTasksCount--}
```
public int getTasksCount()
```


Mendapatkan jumlah tugas


**Returns:**
int - jumlah tugas

### getStartDate() {#getStartDate--}
```
public Date getStartDate()
```


Mendapatkan tanggal mulai Proyek


**Returns:**
java.util.Date - tanggal mulai Proyek

### getEndDate() {#getEndDate--}
```
public Date getEndDate()
```


Mendapatkan tanggal selesai Proyek


**Returns:**
java.util.Date - tanggal selesai Proyek

