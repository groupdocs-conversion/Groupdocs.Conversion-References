---
title: TxtLoadOptions class
second_title: GroupDocs.Conversion for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.conversion.options.load/txtloadoptions/
is_root: false
weight: 420
---


## TxtLoadOptions class

Options for loading Txt documents.

Font Configuration for Plain Text:

Since TXT files don't contain font information, use `DefaultTextFont` to specify the font for rendering the plain text content during conversion.

The TxtLoadOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/__init__/) | Initializes a new instance of [`TxtLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/). |

### Properties
| Property | Description |
| :- | :- |
| [default_font](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/default_font/) | The font used when rendering plain text content during conversion; since TXT files lack font information, this property specifies the display font for the text content (default: Arial 10pt). |
| [detect_numbering_with_whitespaces](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/detect_numbering_with_whitespaces/) | The property allows specifying how numbered list items are recognized when a plain text document is converted. The default value is True. |
| [encoding](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/encoding/) | The encoding used when loading a Txt document; can be None (default). |
| [format](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/format/) | The input document file type. |
| [leading_spaces_options](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/leading_spaces_options/) | The preferred option for handling leading spaces. Default value is [`TxtLeadingSpacesOptions.convert_to_indent`](/conversion/python-net/groupdocs.conversion.options.load/txtleadingspacesoptions/convert_to_indent/). |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/margin_settings/) | The margin settings. |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/size_settings/) | The size settings as defined by `IPageSizeOptions`. |
| [trailing_spaces_options](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/trailing_spaces_options/) | The preferred option for handling trailing spaces. Default value is [`TxtTrailingSpacesOptions.trim`](/conversion/python-net/groupdocs.conversion.options.load/txttrailingspacesoptions/trim/). |

### See Also
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
