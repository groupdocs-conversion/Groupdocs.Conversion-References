---
title: Converter class
second_title: GroupDocs.Conversion for Python via .NET API References
description: 
type: docs
weight: 10
url: /python-net/groupdocs.conversion/converter/
is_root: false
---

## Converter class

Represents main class that controls document conversion process.



The Converter type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#io.RawIOBase) | Initializes new instance of [`Converter`](/conversion/python-net/groupdocs.conversion/converter) class. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#io.RawIOBase-groupdocs.conversion.ConverterSettings) | Initializes new instance of [`Converter`](/conversion/python-net/groupdocs.conversion/converter) class. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#io.RawIOBase-groupdocs.conversion.options.load.LoadOptions) | Initializes new instance of [`Converter`](/conversion/python-net/groupdocs.conversion/converter) class. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#io.RawIOBase-groupdocs.conversion.options.load.LoadOptions-groupdocs.conversion.ConverterSettings) | Initializes new instance of [`Converter`](/conversion/python-net/groupdocs.conversion/converter) class. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#str) | Initializes new instance of [`Converter`](/conversion/python-net/groupdocs.conversion/converter) class. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#str-groupdocs.conversion.ConverterSettings) | Initializes new instance of [`Converter`](/conversion/python-net/groupdocs.conversion/converter) class. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#str-groupdocs.conversion.options.load.LoadOptions) | Initializes new instance of [`Converter`](/conversion/python-net/groupdocs.conversion/converter) class. |
| [__init__](/conversion/python-net/groupdocs.conversion/converter/__init__/#str-groupdocs.conversion.options.load.LoadOptions-groupdocs.conversion.ConverterSettings) | Initializes new instance of [`Converter`](/conversion/python-net/groupdocs.conversion/converter) class. |


### Methods
| Method | Description |
| :- | :- |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#io.RawIOBase-groupdocs.conversion.options.convert.ConvertOptions) | Converts source document. Saves the whole converted document. |
| [convert](/conversion/python-net/groupdocs.conversion/converter/convert/#str-groupdocs.conversion.options.convert.ConvertOptions) | Converts source document. Saves the whole converted document. |
| [convert_by_page](/conversion/python-net/groupdocs.conversion/converter/convert_by_page/#str-groupdocs.conversion.options.convert.ConvertOptions) | Converts source document. Saves the converted document page by page. |
| [convert_by_page](/conversion/python-net/groupdocs.conversion/converter/convert_by_page/#str-int-groupdocs.conversion.options.convert.ConvertOptions) | Converts source document. Saves the converted document page to a stream |
| [convert_by_page](/conversion/python-net/groupdocs.conversion/converter/convert_by_page/#io.RawIOBase-int-groupdocs.conversion.options.convert.ConvertOptions) | Converts source document. Saves the converted document page to a stream |
| [convert_multiple](/conversion/python-net/groupdocs.conversion/converter/convert_multiple/#str-groupdocs.conversion.options.convert.ConvertOptions) | Converts source document to multiple documents of the output format. |
| [get_document_info](/conversion/python-net/groupdocs.conversion/converter/get_document_info/#) | Gets source document info - pages count and other document properties specific to the file type. |
| [is_document_password_protected](/conversion/python-net/groupdocs.conversion/converter/is_document_password_protected/#) | Checks is source document is password protected |
| [get_possible_conversions](/conversion/python-net/groupdocs.conversion/converter/get_possible_conversions/#) | Gets possible conversions for the source document. |
| [get_all_possible_conversions](/conversion/python-net/groupdocs.conversion/converter/get_all_possible_conversions/#) | Gets all supported conversions |
| [get_possible_conversions_by_extension](/conversion/python-net/groupdocs.conversion/converter/get_possible_conversions_by_extension/#str) | Gets supported conversions for provided document extension |



### See Also
* module [`groupdocs.conversion`](..)
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter)
