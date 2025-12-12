---
title: PresentationConvertOptions class
second_title: GroupDocs.Conversion for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.conversion.options.convert/presentationconvertoptions/
is_root: false
weight: 410
---

## PresentationConvertOptions class

Describes options for conversion to Presentation file type.



**Inheritance:** [`PresentationConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/presentationconvertoptions) → 
[`CommonConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/commonconvertoptions) → 
[`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions) → 
[`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject)



The PresentationConvertOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.convert/presentationconvertoptions/__init__/#) | Initializes new instance of [`PresentationConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/presentationconvertoptions) class. |


### Properties
| Property | Description |
| :- | :- |
| [format](/conversion/python-net/groupdocs.conversion.options.convert/presentationconvertoptions/format) | Overrides the Format property to ensure it is of type PresentationFileType. |
| [watermark](/conversion/python-net/groupdocs.conversion.options.convert/presentationconvertoptions/watermark) | Implements [`IWatermarkedConvertOptions.watermark`](/conversion/python-net/groupdocs.conversion.options.convert/iwatermarkedconvertoptions#watermark) |
| [page_number](/conversion/python-net/groupdocs.conversion.options.convert/presentationconvertoptions/page_number) | Implements [`IPagedConvertOptions.page_number`](/conversion/python-net/groupdocs.conversion.options.convert/ipagedconvertoptions#page_number) |
| [pages_count](/conversion/python-net/groupdocs.conversion.options.convert/presentationconvertoptions/pages_count) | Implements [`IPagedConvertOptions.pages_count`](/conversion/python-net/groupdocs.conversion.options.convert/ipagedconvertoptions#pages_count) |
| [pages](/conversion/python-net/groupdocs.conversion.options.convert/presentationconvertoptions/pages) | Implements [`IPageRangedConvertOptions.pages`](/conversion/python-net/groupdocs.conversion.options.convert/ipagerangedconvertoptions#pages) |
| [password](/conversion/python-net/groupdocs.conversion.options.convert/presentationconvertoptions/password) | Set this property if you want to protect the converted document with a password. |
| [zoom](/conversion/python-net/groupdocs.conversion.options.convert/presentationconvertoptions/zoom) | Specifies the zoom level in percentage. Default is 100.<br/>Default zoom is supported till Microsoft Powerpoint 2010. Starting from Microsoft Powerpoint 2013 default zoom is no longer set to document, instead it appears to use the zoom factor of the last document that was opened. |


### Methods
| Method | Description |
| :- | :- |
| [equals](/conversion/python-net/groupdocs.conversion.options.convert/presentationconvertoptions/equals/#groupdocs.conversion.contracts.ValueObject) | Determines whether two object instances are equal. |
| [clone](/conversion/python-net/groupdocs.conversion.options.convert/presentationconvertoptions/clone/#) | Clones current options instance. |



### See Also
* module [`groupdocs.conversion.options.convert`](..)
* class [`CommonConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/commonconvertoptions)
* class [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions)
* class [`PresentationConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/presentationconvertoptions)
* class [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject)
