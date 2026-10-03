---
title: "ProjectManagementDocumentInfo"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "ProjectManagement दस्तावेज़ मेटाडेटा शामिल है"
type: docs
weight: 32
url: /hi/java/com.groupdocs.conversion.contracts.documentinfo/projectmanagementdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class ProjectManagementDocumentInfo extends DocumentInfo
```

ProjectManagement दस्तावेज़ मेटाडेटा शामिल है

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [ProjectManagementDocumentInfo(Project project, FileType format, long size)](#ProjectManagementDocumentInfo-com.aspose.tasks.Project-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getTasksCount()](#getTasksCount--) | कार्य की संख्या प्राप्त करता है |
|
|  | [getStartDate()](#getStartDate--) | प्राप्त करता है Project प्रारंभ तिथि |
|
|  | [getEndDate()](#getEndDate--) | प्राप्त करता है Project समाप्ति तिथि |
|
### ProjectManagementDocumentInfo(Project project, FileType format, long size) {#ProjectManagementDocumentInfo-com.aspose.tasks.Project-com.groupdocs.conversion.filetypes.FileType-long-}
```
public ProjectManagementDocumentInfo(Project project, FileType format, long size)
```


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| परियोजना | com.aspose.tasks.Project |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| आकार | long |  |

### getTasksCount() {#getTasksCount--}
```
public int getTasksCount()
```


कार्य की संख्या प्राप्त करता है


**Returns:**
int - कार्य की संख्या

### getStartDate() {#getStartDate--}
```
public Date getStartDate()
```


प्राप्त करता है Project प्रारंभ तिथि


**Returns:**
java.util.Date - Project प्रारंभ तिथि

### getEndDate() {#getEndDate--}
```
public Date getEndDate()
```


प्राप्त करता है Project समाप्ति तिथि


**Returns:**
java.util.Date - Project समाप्ति तिथि

