---
title: ProjectManagementFileType class
second_title: GroupDocs.Conversion for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/
is_root: false
weight: 160
---

## ProjectManagementFileType class

Defines Project file formats that are created by Project Management software such as Microsoft Project, Primavera P6 etc. A project file is a collection of tasks, resources, and their scheduling to get a measurable output in the form or a product or a service. 
Project management documents. Includes the following file types:
[`ProjectManagementFileType.Mpp`](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype),
[`ProjectManagementFileType.Mpt`](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype),
[`ProjectManagementFileType.Mpx`](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype).
Learn more about Project Management formats [here](https://wiki.fileformat.com/project-management).



**Inheritance:** [`ProjectManagementFileType`](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype) → 
[`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype) → 
[`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration)



The ProjectManagementFileType type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/__init__/#) | Serialization constructor |


### Properties
| Property | Description |
| :- | :- |
| [file_format](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/file_format) | The file format |
| [extension](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/extension) | The file extension |
| [family](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/family) | The file family |
| [description](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/description) | File type description |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/unknown) | Unknown file type |
| [MPT](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/mpt) | Microsoft Project template files, contain basic information and structure along with document settings for creating .MPP files.<br/>Learn more about this file format [here](https://wiki.fileformat.com/project-management/mpt). |
| [MPP](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/mpp) | MPP is Microsoft Project data file that stores information related to project management in an integrated manner.<br/>Learn more about this file format [here](https://wiki.fileformat.com/project-management/mpp). |
| [MPX](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/mpx) | Microsoft Exchange File Format, is an ASCII file format for transferring of project information between Microsoft Project (MSP) and other applications that support the MPX file format such as Primavera Project Planner, Sciforma and Timerline Precision Estimating.<br/>Learn more about this file format [here](https://wiki.fileformat.com/project-management/mpx). |
| [XER](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/xer) | The XER file format is a proprietary project file format used by Primavera P6 project planning and management application.<br/>Learn more about this file format [here](https://docs.fileformat.com/project-management/xer). |


### Methods
| Method | Description |
| :- | :- |
| [equals](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/equals/#groupdocs.conversion.contracts.Enumeration) | Implements [`Enumeration.equals`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals) |
| [compare_to](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/compare_to/#System.Object) | Compares current object to other. |
| [from_filename](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/from_filename/#System.String) | Returns FileType for specified fileName |
| [from_extension](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/from_extension/#System.String) | Gets FileType for provided fileExtension |
| [from_stream](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/from_stream/#io.RawIOBase) | Returns FileType for provided document stream |



### See Also
* module [`groupdocs.conversion.filetypes`](..)
* class [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration)
* class [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype)
* class [`ProjectManagementFileType`](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype)
