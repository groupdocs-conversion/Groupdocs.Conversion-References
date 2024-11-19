---
title: ImageConvertOptions class
second_title: GroupDocs.Conversion for Python via .NET API References
description: 
type: docs
weight: 200
url: /python-net/groupdocs.conversion.options.convert/imageconvertoptions/
is_root: false
---

## ImageConvertOptions class

Options for conversion to Image file type.



**Inheritance:** [`ImageConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions) → 
[`CommonConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/commonconvertoptions) → 
[`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions) → 
[`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject)



The ImageConvertOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/__init__/#) | Initializes new instance of [`ImageConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions) class. |


### Properties
| Property | Description |
| :- | :- |
| [format](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/format) | Overrides the Format property to ensure it is of type ImageFileType. |
| [watermark](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/watermark) | Implements [`IWatermarkedConvertOptions.watermark`](/conversion/python-net/groupdocs.conversion.options.convert/iwatermarkedconvertoptions#watermark) |
| [page_number](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/page_number) | Implements [`IPagedConvertOptions.page_number`](/conversion/python-net/groupdocs.conversion.options.convert/ipagedconvertoptions#page_number) |
| [pages_count](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/pages_count) | Implements [`IPagedConvertOptions.pages_count`](/conversion/python-net/groupdocs.conversion.options.convert/ipagedconvertoptions#pages_count) |
| [pages](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/pages) | Implements [`IPageRangedConvertOptions.pages`](/conversion/python-net/groupdocs.conversion.options.convert/ipagerangedconvertoptions#pages) |
| [width](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/width) | Desired image width after conversion. |
| [height](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/height) | Desired image height after conversion. |
| [use_pdf](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/use_pdf) | If `true`, the input firstly is converted to PDF and after that to desired format. |
| [horizontal_resolution](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/horizontal_resolution) | Desired image horizontal resolution after conversion. The default resolution is the resolution of the input file or 96 dpi. |
| [vertical_resolution](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/vertical_resolution) | Desired image vertical resolution after conversion. The default resolution is the resolution of the input file or 96 dpi. |
| [tiff_options](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/tiff_options) | Tiff specific convert options. |
| [psd_options](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/psd_options) | Psd specific convert options. |
| [webp_options](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/webp_options) | Webp specific convert options. |
| [grayscale](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/grayscale) | Indicates whether to convert into grayscale image. |
| [rotate_angle](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/rotate_angle) | Image rotation angle. |
| [jpeg_options](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/jpeg_options) | Jpeg specific convert options. |
| [flip_mode](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/flip_mode) | Image flip mode. |
| [brightness](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/brightness) | Adjusts image brightness. |
| [contrast](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/contrast) | Adjusts image contrast. |
| [gamma](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/gamma) | Adjusts image gamma. |
| [background_color](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/background_color) | Sets background color where supported by the source format |


### Methods
| Method | Description |
| :- | :- |
| [equals](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/equals/#groupdocs.conversion.contracts.ValueObject) | Determines whether two object instances are equal. |
| [clone](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/clone/#) | Clones current options instance. |



### See Also
* module [`groupdocs.conversion.options.convert`](..)
* class [`CommonConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/commonconvertoptions)
* class [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions)
* class [`ImageConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions)
* class [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject)
