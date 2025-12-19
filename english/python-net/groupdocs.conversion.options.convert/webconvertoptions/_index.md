---
title: WebConvertOptions class
second_title: GroupDocs.Conversion for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.conversion.options.convert/webconvertoptions/
is_root: false
weight: 550
---

## WebConvertOptions class

Options for conversion to Web file type.



**Inheritance:** [`WebConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/webconvertoptions) → 
[`CommonConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/commonconvertoptions) → 
[`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions) → 
[`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject)



The WebConvertOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.convert/webconvertoptions/__init__/#) | Initializes new instance of [`WebConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/webconvertoptions) class. |


### Properties
| Property | Description |
| :- | :- |
| [format](/conversion/python-net/groupdocs.conversion.options.convert/webconvertoptions/format) | Overrides the Format property to ensure it is of type WebFileType. |
| [watermark](/conversion/python-net/groupdocs.conversion.options.convert/webconvertoptions/watermark) | Implements [`IWatermarkedConvertOptions.watermark`](/conversion/python-net/groupdocs.conversion.options.convert/iwatermarkedconvertoptions#watermark) |
| [page_number](/conversion/python-net/groupdocs.conversion.options.convert/webconvertoptions/page_number) | Implements [`IPagedConvertOptions.page_number`](/conversion/python-net/groupdocs.conversion.options.convert/ipagedconvertoptions#page_number) |
| [pages_count](/conversion/python-net/groupdocs.conversion.options.convert/webconvertoptions/pages_count) | Implements [`IPagedConvertOptions.pages_count`](/conversion/python-net/groupdocs.conversion.options.convert/ipagedconvertoptions#pages_count) |
| [pages](/conversion/python-net/groupdocs.conversion.options.convert/webconvertoptions/pages) | Implements [`IPageRangedConvertOptions.pages`](/conversion/python-net/groupdocs.conversion.options.convert/ipagerangedconvertoptions#pages) |
| [use_pdf](/conversion/python-net/groupdocs.conversion.options.convert/webconvertoptions/use_pdf) | If `true`, the input firstly is converted to PDF and after that to desired format |
| [fixed_layout](/conversion/python-net/groupdocs.conversion.options.convert/webconvertoptions/fixed_layout) | If `true` fixed layout will be used e.g. absolutely positioned html elements<br/>Default:  true |
| [fixed_layout_show_borders](/conversion/python-net/groupdocs.conversion.options.convert/webconvertoptions/fixed_layout_show_borders) | Show page borders when converting to fixed layout. Default is True. |
| [zoom](/conversion/python-net/groupdocs.conversion.options.convert/webconvertoptions/zoom) | Specifies the zoom level in percentage. Default is 100. |
| [embed_font_resources](/conversion/python-net/groupdocs.conversion.options.convert/webconvertoptions/embed_font_resources) | Specifies whether to embed font resources within the main HTML. Default is false.<br/>Note: If FixedLayout is set to true, font resources will always be embedded. |


### Methods
| Method | Description |
| :- | :- |
| [equals](/conversion/python-net/groupdocs.conversion.options.convert/webconvertoptions/equals/#groupdocs.conversion.contracts.ValueObject) | Determines whether two object instances are equal. |
| [clone](/conversion/python-net/groupdocs.conversion.options.convert/webconvertoptions/clone/#) | Clones current options instance. |



### See Also
* module [`groupdocs.conversion.options.convert`](..)
* class [`CommonConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/commonconvertoptions)
* class [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions)
* class [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject)
* class [`WebConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/webconvertoptions)
