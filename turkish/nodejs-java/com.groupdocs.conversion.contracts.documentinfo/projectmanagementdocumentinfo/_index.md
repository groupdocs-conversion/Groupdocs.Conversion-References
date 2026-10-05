---
title: "ProjectManagementDocumentInfo"
second_title: "Node.js için GroupDocs.Conversion, Java üzerinden API Referansı"
description: "ProjectManagement belge meta verilerini içerir"
type: docs
weight: 35
url: /tr/nodejs-java/com.groupdocs.conversion.contracts.documentinfo/projectmanagementdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class ProjectManagementDocumentInfo extends DocumentInfo
```

ProjectManagement belge meta verilerini içerir
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ProjectManagementDocumentInfo(Project project, FileType format, long size)](#ProjectManagementDocumentInfo-com.aspose.tasks.Project-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getTasksCount()](#getTasksCount--) | Görev sayısını alır |
| [getStartDate()](#getStartDate--) | Proje başlangıç tarihini alır |
| [getEndDate()](#getEndDate--) | Proje bitiş tarihini alır |
### ProjectManagementDocumentInfo(Project project, FileType format, long size) {#ProjectManagementDocumentInfo-com.aspose.tasks.Project-com.groupdocs.conversion.filetypes.FileType-long-}
```
public ProjectManagementDocumentInfo(Project project, FileType format, long size)
```


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| proje | com.aspose.tasks.Project |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |

### getTasksCount() {#getTasksCount--}
```
public int getTasksCount()
```


Görev sayısını alır

**Returns:**
int - görev sayısı
### getStartDate() {#getStartDate--}
```
public Date getStartDate()
```


Proje başlangıç tarihini alır

**Returns:**
java.util.Date - Proje başlangıç tarihi
### getEndDate() {#getEndDate--}
```
public Date getEndDate()
```


Proje bitiş tarihini alır

**Returns:**
java.util.Date - Proje bitiş tarihi
