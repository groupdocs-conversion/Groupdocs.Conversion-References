---
title: DatabaseFileType class
second_title: GroupDocs.Conversion for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.conversion.filetypes/databasefiletype/
is_root: false
weight: 30
---

## DatabaseFileType class

Defines database documents. Includes the following file types:
[`DatabaseFileType.Nsf`](/conversion/python-net/groupdocs.conversion.filetypes/databasefiletype)[`DatabaseFileType.Log`](/conversion/python-net/groupdocs.conversion.filetypes/databasefiletype)[`DatabaseFileType.Sql`](/conversion/python-net/groupdocs.conversion.filetypes/databasefiletype)



**Inheritance:** [`DatabaseFileType`](/conversion/python-net/groupdocs.conversion.filetypes/databasefiletype) → 
[`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype) → 
[`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration)



The DatabaseFileType type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/databasefiletype/__init__/#) | Serialization constructor |


### Properties
| Property | Description |
| :- | :- |
| [file_format](/conversion/python-net/groupdocs.conversion.filetypes/databasefiletype/file_format) | The file format |
| [extension](/conversion/python-net/groupdocs.conversion.filetypes/databasefiletype/extension) | The file extension |
| [family](/conversion/python-net/groupdocs.conversion.filetypes/databasefiletype/family) | The file family |
| [description](/conversion/python-net/groupdocs.conversion.filetypes/databasefiletype/description) | File type description |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/databasefiletype/unknown) | Unknown file type |
| [NSF](/conversion/python-net/groupdocs.conversion.filetypes/databasefiletype/nsf) | A file with .nsf (Notes Storage Facility) extension is a database file format used by the IBM Notes software, which was previously known as Lotus Notes. It defines the schema to store different kind of objects such like emails, appointments, documents, forms and views.<br/>Learn more about this file format [here](https://docs.fileformat.com/database/nsf). |
| [LOG](/conversion/python-net/groupdocs.conversion.filetypes/databasefiletype/log) | A file with .log extension contains the list of plain text with timestamp. Usually, certain activity detail is logged by the softwares or operating systems to help the developers or users to track what was happening at a certain time period. <br/>Learn more about this file format [here](https://docs.fileformat.com/database/log). |
| [SQL](/conversion/python-net/groupdocs.conversion.filetypes/databasefiletype/sql) | A file with .sql extension is a Structured Query Language (SQL) file that contains code to work with relational databases. It is used to write SQL statements for CRUD (Create, Read, Update, and Delete) operations on databases. <br/>Learn more about this file format [here](https://docs.fileformat.com/database/sql). |


### Methods
| Method | Description |
| :- | :- |
| [equals](/conversion/python-net/groupdocs.conversion.filetypes/databasefiletype/equals/#groupdocs.conversion.contracts.Enumeration) | Implements [`Enumeration.equals`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals) |
| [compare_to](/conversion/python-net/groupdocs.conversion.filetypes/databasefiletype/compare_to/#System.Object) | Compares current object to other. |
| [from_filename](/conversion/python-net/groupdocs.conversion.filetypes/databasefiletype/from_filename/#System.String) | Returns FileType for specified fileName |
| [from_extension](/conversion/python-net/groupdocs.conversion.filetypes/databasefiletype/from_extension/#System.String) | Gets FileType for provided fileExtension |
| [from_stream](/conversion/python-net/groupdocs.conversion.filetypes/databasefiletype/from_stream/#io.RawIOBase) | Returns FileType for provided document stream |



### See Also
* module [`groupdocs.conversion.filetypes`](..)
* class [`DatabaseFileType`](/conversion/python-net/groupdocs.conversion.filetypes/databasefiletype)
* class [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration)
* class [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype)
