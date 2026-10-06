---
title: "DocumentInfo klasse"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "De basisimplementatie voor het ophalen van polymorfe documentinformatie."
type: docs
url: /nl/python-net/groupdocs.conversion.contracts/documentinfo/
is_root: false
weight: 120
---


## DocumentInfo class

De basisimplementatie voor het ophalen van polymorfe documentinformatie.

Instanties worden geretourneerd door `Converter.get_document_info()` en geven metadata weer, zoals formaat, paginatelling, aanmaakdatum, grootte en formaat‑specifieke attributen.

Het DocumentInfo type maakt de volgende leden beschikbaar:

### Methoden
| Methode | Beschrijving |
| :- | :- |
| [get](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/get/) |  |
| [get_file](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/get_file/) |  |
| [get_string](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/get_string/) |  |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [creation_date](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/creation_date/) | De aanmaakdatum van het document. |
| [format](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/format/) | Het formaat van het document. |
| [pages_count](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/pages_count/) | Het totale aantal pagina's in het document. |
| [property_names](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/property_names/) | De eigenschap implementeert [`IDocumentInfo.property_names`](/conversion/python-net/groupdocs.conversion.contracts/idocumentinfo/property_names/). |
| [size](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/size/) | De grootte van het document in bytes. |

### Voorbeeld

```python
from groupdocs.conversion import Converter

def show_document_info(path):
    with Converter(path) as converter:
        info = converter.get_document_info()
        print("Format:", info.format)
        print("Pages count:", info.pages_count)
        print("Creation date:", info.creation_date)
        print("Size (bytes):", info.size)

# Voorbeeldgebruik
show_document_info("./lorem-ipsum.txt")
```

### Zie ook
* module [`groupdocs.conversion.contracts`](/conversion/python-net/groupdocs.conversion.contracts/)
