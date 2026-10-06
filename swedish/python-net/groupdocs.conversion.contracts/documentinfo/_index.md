---
title: "Klassen DocumentInfo"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Den grundläggande implementeringen för att hämta polymorfisk dokumentinformation."
type: docs
url: /sv/python-net/groupdocs.conversion.contracts/documentinfo/
is_root: false
weight: 120
---


## DocumentInfo class

Den grundläggande implementeringen för att hämta polymorfisk dokumentinformation.

Instanser returneras av `Converter.get_document_info()` och exponerar metadata såsom format, sidantal, skapelsedatum, storlek och format‑specifika attribut.

Typen DocumentInfo exponerar följande medlemmar:

### Metoder
| Metod | Beskrivning |
| :- | :- |
| [get](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/get/) |  |
| [get_file](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/get_file/) |  |
| [get_string](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/get_string/) |  |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [creation_date](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/creation_date/) | Dokumentets skapelsedatum. |
| [format](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/format/) | Dokumentets format. |
| [pages_count](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/pages_count/) | Det totala antalet sidor i dokumentet. |
| [property_names](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/property_names/) | Egenskapen implementerar [`IDocumentInfo.property_names`](/conversion/python-net/groupdocs.conversion.contracts/idocumentinfo/property_names/). |
| [size](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/size/) | Dokumentets storlek i byte. |

### Exempel

```python
from groupdocs.conversion import Converter

def show_document_info(path):
    with Converter(path) as converter:
        info = converter.get_document_info()
        print("Format:", info.format)
        print("Pages count:", info.pages_count)
        print("Creation date:", info.creation_date)
        print("Size (bytes):", info.size)

# Exempel på användning
show_document_info("./lorem-ipsum.txt")
```

### Se även
* module [`groupdocs.conversion.contracts`](/conversion/python-net/groupdocs.conversion.contracts/)
