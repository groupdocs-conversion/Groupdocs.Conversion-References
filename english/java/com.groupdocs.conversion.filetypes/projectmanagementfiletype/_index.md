---
title: ProjectManagementFileType
second_title: GroupDocs.Conversion for Java API Reference
description: Defines Project file formats that are created by Project Management software such as Microsoft Project Primavera P6 etc.
type: docs
weight: 22
url: /java/com.groupdocs.conversion.filetypes/projectmanagementfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)
```
public final class ProjectManagementFileType extends FileType
```

Defines Project file formats that are created by Project Management software such as Microsoft Project, Primavera P6 etc. A project file is a collection of tasks, resources, and their scheduling to get a measurable output in the form or a product or a service. Project management documents. Includes the following file types: [Mpp](../../com.groupdocs.conversion.filetypes/projectmanagementfiletype\#Mpp), [Mpt](../../com.groupdocs.conversion.filetypes/projectmanagementfiletype\#Mpt), [Mpx](../../com.groupdocs.conversion.filetypes/projectmanagementfiletype\#Mpx). Learn more about Project Management formats [here][].


[here]: https://wiki.fileformat.com/project-management
## Constructors

| Constructor | Description |
| --- | --- |
| [ProjectManagementFileType()](#ProjectManagementFileType--) | Serialization constructor |
## Fields

| Field | Description |
| --- | --- |
| [Mpt](#Mpt) | Microsoft Project template files, contain basic information and structure along with document settings for creating .MPP files. |
| [Mpp](#Mpp) | MPP is Microsoft Project data file that stores information related to project management in an integrated manner. |
| [Mpx](#Mpx) | Microsoft Exchange File Format, is an ASCII file format for transferring of project information between Microsoft Project (MSP) and other applications that support the MPX file format such as Primavera Project Planner, Sciforma and Timerline Precision Estimating. |
| [Xer](#Xer) | The XER file format is a proprietary project file format used by Primavera P6 project planning and management application. |
## Methods

| Method | Description |
| --- | --- |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### ProjectManagementFileType() {#ProjectManagementFileType--}
```
public ProjectManagementFileType()
```


Serialization constructor

### Mpt {#Mpt}
```
public static final ProjectManagementFileType Mpt
```


Microsoft Project template files, contain basic information and structure along with document settings for creating .MPP files. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/project-management/mpt

### Mpp {#Mpp}
```
public static final ProjectManagementFileType Mpp
```


MPP is Microsoft Project data file that stores information related to project management in an integrated manner. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/project-management/mpp

### Mpx {#Mpx}
```
public static final ProjectManagementFileType Mpx
```


Microsoft Exchange File Format, is an ASCII file format for transferring of project information between Microsoft Project (MSP) and other applications that support the MPX file format such as Primavera Project Planner, Sciforma and Timerline Precision Estimating. Learn more about this file format [here][].


[here]: https://wiki.fileformat.com/project-management/mpx

### Xer {#Xer}
```
public static final ProjectManagementFileType Xer
```


The XER file format is a proprietary project file format used by Primavera P6 project planning and management application. Learn more about this file format [here][].


[here]: https://docs.fileformat.com/project-management/xer

### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Prepared default convert options for the file type

**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static final FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
