---
title: DocumentInfo class
second_title: GroupDocs.Conversion for Python via .NET API References
description: "The base implementation for retrieving polymorphic document information."
type: docs
url: /python-net/groupdocs.conversion.contracts/documentinfo/
is_root: false
weight: 120
---


## DocumentInfo class

The base implementation for retrieving polymorphic document information.

Instances are returned by `Converter.get_document_info()` and expose metadata such as format, page count, creation date, size, and format‑specific attributes.

The DocumentInfo type exposes the following members:

### Methods
| Method | Description |
| :- | :- |
| [get](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/get/) |  |
| [get_file](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/get_file/) |  |
| [get_string](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/get_string/) |  |

### Properties
| Property | Description |
| :- | :- |
| [creation_date](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/creation_date/) | The creation date of the document. |
| [format](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/format/) | The format of the document. |
| [pages_count](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/pages_count/) | The total number of pages in the document. |
| [property_names](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/property_names/) | The property implements [`IDocumentInfo.property_names`](/conversion/python-net/groupdocs.conversion.contracts/idocumentinfo/property_names/). |
| [size](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/size/) | The size of the document in bytes. |

### Example

```python
from groupdocs.conversion import Converter

def show_document_info(path):
    with Converter(path) as converter:
        info = converter.get_document_info()
        print("Format:", info.format)
        print("Pages count:", info.pages_count)
        print("Creation date:", info.creation_date)
        print("Size (bytes):", info.size)

# Example usage
show_document_info("./lorem-ipsum.txt")
```

### See Also
* module [`groupdocs.conversion.contracts`](/conversion/python-net/groupdocs.conversion.contracts/)
