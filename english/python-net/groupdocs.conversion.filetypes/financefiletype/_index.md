---
title: FinanceFileType class
second_title: GroupDocs.Conversion for Python via .NET API References
description: 
type: docs
weight: 80
url: /python-net/groupdocs.conversion.filetypes/financefiletype/
is_root: false
---

## FinanceFileType class

Defines Finance documents
Includes the following types:
[`FinanceFileType.Xbrl`](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype)[`FinanceFileType.IXbrl`](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype)[`FinanceFileType.Ofx`](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype)
Learn more about Finance formats [here](https://docs.fileformat.com/finance/).



**Inheritance:** [`FinanceFileType`](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype) → 
[`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype) → 
[`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration)



The FinanceFileType type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/__init__/#) | Serialization constructor |


### Properties
| Property | Description |
| :- | :- |
| [file_format](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/file_format) | The file format |
| [extension](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/extension) | The file extension |
| [family](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/family) | The file family |
| [description](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/description) | File type description |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/unknown) | Unknown file type |
| [XBRL](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/xbrl) | XBRL is an open international standard for digital business reporting that is widely used globally. It is an XML based language that uses XBRL elements, known as tags, to describe each item of business data to formulate data for report sorting and analysis.<br/>Learn more about this file format [here](https://docs.fileformat.com/finance/xbrl/). |
| [I_XBRL](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/i_xbrl) | Inside the iXBRL, contents of XBRL are wrapped in xHTML file format that uses XML tags. Like XBRL, is the root element of iXBRL files. The XHTML format represents its contents as collection of different document types and modules. All the files in XHTML are based on XML file format and conform to the XML document standards.<br/>Learn more about this file format [here](https://docs.fileformat.com/finance/ixbrl/). |
| [OFX](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/ofx) | Open Financial Exchange (OFX) is a data-stream format for exchanging financial information that evolved from Microsoft's Open Financial Connectivity (OFC) and Intuit's Open Exchange file formats.<br/>Learn more about this file format [here](https://en.wikipedia.org/wiki/Open_Financial_Exchange). |


### Methods
| Method | Description |
| :- | :- |
| [equals](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/equals/#groupdocs.conversion.contracts.Enumeration) | Implements [`Enumeration.equals`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals) |
| [compare_to](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/compare_to/#any) | Compares current object to other. |
| [from_filename](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/from_filename/#str) | Returns FileType for specified fileName |
| [from_extension](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/from_extension/#str) | Gets FileType for provided fileExtension |
| [from_stream](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/from_stream/#io.RawIOBase) | Returns FileType for provided document stream |



### See Also
* module [`groupdocs.conversion.filetypes`](..)
* class [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration)
* class [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype)
* class [`FinanceFileType`](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype)
