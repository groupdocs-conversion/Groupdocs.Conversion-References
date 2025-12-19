---
title: EmailFileType class
second_title: GroupDocs.Conversion for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.conversion.filetypes/emailfiletype/
is_root: false
weight: 60
---

## EmailFileType class

Defines Email file formats that are used by email applications to store their various data including email messages, attachments, folders, address books etc.
Includes the following file types:
[`EmailFileType.Eml`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype),
[`EmailFileType.Emlx`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype),
[`EmailFileType.Msg`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype),
[`EmailFileType.Vcf`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype).
[`EmailFileType.Mbox`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype).
[`EmailFileType.Pst`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype).
[`EmailFileType.Ost`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype).
[`EmailFileType.Olm`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype).
Learn more about Email formats [here](https://wiki.fileformat.com/email).



**Inheritance:** [`EmailFileType`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype) → 
[`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype) → 
[`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration)



The EmailFileType type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/__init__/#) | Serialization constructor |


### Properties
| Property | Description |
| :- | :- |
| [file_format](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/file_format) | The file format |
| [extension](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/extension) | The file extension |
| [family](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/family) | The file family |
| [description](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/description) | File type description |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/unknown) | Unknown file type |
| [MSG](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/msg) | MSG is a file format used by Microsoft Outlook and Exchange to store email messages, contact, appointment, or other tasks.<br/>Learn more about this file format [here](https://wiki.fileformat.com/email/msg). |
| [EML](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/eml) | EML file format represents email messages saved using Outlook and other relevant applications. Almost all emailing clients support this file format for its compliance with RFC-822 Internet Message Format Standard. <br/>Learn more about this file format [here](https://wiki.fileformat.com/email/eml). |
| [EMLX](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/emlx) | The EMLX file format is implemented and developed by Apple. The Apple Mail application uses the EMLX file format for exporting the emails.<br/>Learn more about this file format [here](https://wiki.fileformat.com/email/emlx). |
| [VCF](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/vcf) | VCF (Virtual Card Format) or vCard is a digital file format for storing contact information. The format is widely used for data interchange among popular information exchange applications.<br/>Learn more about this file format [here](https://wiki.fileformat.com/email/vcf). |
| [MBOX](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/mbox) | MBox file format is a generic term that represents a container for collection of electronic mail messages. The messages are stored inside the container along with their attachments.<br/>Learn more about this file format [here](https://docs.fileformat.com/email/mbox/). |
| [PST](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/pst) | Files with .PST extension represent Outlook Personal Storage Files (also called Personal Storage Table) that store variety of user information.<br/>Learn more about this file format [here](https://wiki.fileformat.com/email/pst). |
| [OST](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/ost) | OST or Offline Storage Files represent user's mailbox data in offline mode on local machine upon registration with Exchange Server using Microsoft Outlook. <br/>Learn more about this file format [here](https://wiki.fileformat.com/email/ost). |
| [OLM](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/olm) | A file with .olm extension is a Microsoft Outlook file for Mac Operating System. An OLM file stores email messages, journals, calendar data, and other types of application data. These are similar to PST files used by Outlook on Windows Operating System. However, OLM files created by Outlook for Mac can’t be opened in Outlook for Windows.<br/>Learn more about this file format [here](https://wiki.fileformat.com/email/olm). |


### Methods
| Method | Description |
| :- | :- |
| [equals](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/equals/#groupdocs.conversion.contracts.Enumeration) | Implements [`Enumeration.equals`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals) |
| [compare_to](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/compare_to/#System.Object) | Compares current object to other. |
| [from_filename](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/from_filename/#System.String) | Returns FileType for specified fileName |
| [from_extension](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/from_extension/#System.String) | Gets FileType for provided fileExtension |
| [from_stream](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/from_stream/#io.RawIOBase) | Returns FileType for provided document stream |



### See Also
* module [`groupdocs.conversion.filetypes`](..)
* class [`EmailFileType`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype)
* class [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration)
* class [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype)
