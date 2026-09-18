---
title: PresentationFileType class
second_title: GroupDocs.Conversion for Python via .NET API References
description: "Represents presentation file formats that store a collection of records to accommodate presentation data such as slides, shapes, text, animations, video, audio and embedded objects."
type: docs
url: /python-net/groupdocs.conversion.filetypes/presentationfiletype/
is_root: false
weight: 160
---


## PresentationFileType class

Represents presentation file formats that store a collection of records to accommodate presentation data such as slides, shapes, text, animations, video, audio and embedded objects.

Includes the following file types:
- [`PresentationFileType.odp`](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/odp/)
- [`PresentationFileType.otp`](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/otp/)
- [`PresentationFileType.pot`](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/pot/)
- [`PresentationFileType.potm`](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/potm/)
- [`PresentationFileType.potx`](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/potx/)
- [`PresentationFileType.pps`](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/pps/)
- [`PresentationFileType.ppsm`](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/ppsm/)
- [`PresentationFileType.ppsx`](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/ppsx/)
- [`PresentationFileType.ppt`](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/ppt/)
- [`PresentationFileType.pptm`](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/pptm/)
- [`PresentationFileType.pptx`](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/pptx/).

Learn more about presentation formats at https://wiki.fileformat.com/presentation.

The PresentationFileType type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/__init__/) | Initializes a PresentationFileType for serialization. |

### Methods
| Method | Description |
| :- | :- |
| [compare_to](/conversion/python-net/groupdocs.conversion.contracts/enumeration/compare_to/) | Compares current object to other. (inherited from [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [compare_to_object](/conversion/python-net/groupdocs.conversion.contracts/enumeration/compare_to_object/) |  (inherited from [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [equals](/conversion/python-net/groupdocs.conversion.filetypes/filetype/equals/) | Implements the equality comparison defined by [`Enumeration.equals`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals/). (inherited from [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [equals_enumeration](/conversion/python-net/groupdocs.conversion.filetypes/filetype/equals_enumeration/) |  (inherited from [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals_object/) |  (inherited from [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [from_display_name](/conversion/python-net/groupdocs.conversion.contracts/enumeration/from_display_name/) |  (inherited from [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [from_extension](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_extension/) | Gets the FileType for the provided file extension. (inherited from [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_filename](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_filename/) | Returns FileType for specified file_name. (inherited from [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_stream](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_stream/) | Returns FileType for provided document stream. (inherited from [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_value](/conversion/python-net/groupdocs.conversion.contracts/enumeration/from_value/) |  (inherited from [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [get_all](/conversion/python-net/groupdocs.conversion.filetypes/filetype/get_all/) |  (inherited from [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/enumeration/get_hash_code/) | Provides the default hash function. (inherited from [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [to_string](/conversion/python-net/groupdocs.conversion.filetypes/filetype/to_string/) | String representation of file type. (inherited from [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Properties
| Property | Description |
| :- | :- |
| [description](/conversion/python-net/groupdocs.conversion.filetypes/filetype/description/) | The file type description. (inherited from [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [extension](/conversion/python-net/groupdocs.conversion.filetypes/filetype/extension/) | The file extension. (inherited from [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [family](/conversion/python-net/groupdocs.conversion.filetypes/filetype/family/) | The file family. (inherited from [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [file_format](/conversion/python-net/groupdocs.conversion.filetypes/filetype/file_format/) | The file format. (inherited from [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Fields
| Field | Description |
| :- | :- |
| [PPT](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/ppt/) | A file with PPT extension represents PowerPoint file that consists of a collection of slides for displaying as SlideShow. It specifies the Binary File Format used by Microsoft PowerPoint 97-2003. Learn more about this file format here. |
| [PPS](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/pps/) | PPS, PowerPoint Slide Show, files are created using Microsoft PowerPoint for Slide Show purpose. PPS file reading and creation is supported by Microsoft PowerPoint 97-2003. Learn more about this file format here. |
| [PPTX](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/pptx/) | Files with PPTX extension are presentation files created with popular Microsoft PowerPoint application. Unlike the previous version of presentation file format PPT which was binary, the PPTX format is based on the Microsoft PowerPoint open XML presentation file format. Learn more about this file format here. |
| [PPSX](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/ppsx/) | PPSX, Power Point Slide Show, file are created using Microsoft PowerPoint 2007 and above for Slide Show purpose. Learn more about this file format here. |
| [ODP](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/odp/) | Files with ODP extension represent presentation file format used by OpenOffice.org in the OASISOpen standard. Learn more about this file format here. |
| [OTP](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/otp/) | Files with .OTP extension represent presentation template files created by applications in OASIS OpenDocument standard format. Learn more about this file format here. |
| [POTX](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/potx/) | Files with .POTX extension represent Microsoft PowerPoint template presentations that are created with Microsoft PowerPoint 2007 and above. Learn more about this file format here. |
| [POT](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/pot/) | Files with .POT extension represent Microsoft PowerPoint template files created by PowerPoint 97-2003 versions. Learn more about this file format here. |
| [POTM](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/potm/) | Files with POTM extension are Microsoft PowerPoint template files with support for Macros. POTM files are created with PowerPoint 2007 or above and contains default settings that can be used to create further presentation files. Learn more about this file format here. |
| [PPTM](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/pptm/) | Files with PPTM extension are Macro-enabled Presentation files that are created with Microsoft PowerPoint 2007 or higher versions. Learn more about this file format here. |
| [PPSM](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/ppsm/) | Files with PPSM extension represent Macro-enabled Slide Show file format created with Microsoft PowerPoint 2007 or higher. Learn more about this file format here. |
| [FODP](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/fodp/) | Files with FODP extension represent OpenDocument Flat XML Presentation. Presentation file saved in the OpenDocument format, but saved using a flat XML format instead of the .ZIP container used by standard .ODP files |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/filetype/unknown/) | Unknown file type (inherited from [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### See Also
* module [`groupdocs.conversion.filetypes`](/conversion/python-net/groupdocs.conversion.filetypes/)
