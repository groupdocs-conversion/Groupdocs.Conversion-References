---
title: "classe DocumentInfo"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "L'implémentation de base pour récupérer les informations polymorphes du document."
type: docs
url: /fr/python-net/groupdocs.conversion.contracts/documentinfo/
is_root: false
weight: 120
---


## DocumentInfo class

L'implémentation de base pour récupérer les informations polymorphes du document.

Les instances sont renvoyées par `Converter.get_document_info()` et exposent des métadonnées telles que le format, le nombre de pages, la date de création, la taille et les attributs spécifiques au format.

Le type DocumentInfo expose les membres suivants:

### Méthodes
| Méthode | Description |
| :- | :- |
| [get](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/get/) |  |
| [get_file](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/get_file/) |  |
| [get_string](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/get_string/) |  |

### Propriétés
| Propriété | Description |
| :- | :- |
| [creation_date](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/creation_date/) | La date de création du document. |
| [format](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/format/) | Le format du document. |
| [pages_count](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/pages_count/) | Le nombre total de pages du document. |
| [property_names](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/property_names/) | La propriété implémente [`IDocumentInfo.property_names`](/conversion/python-net/groupdocs.conversion.contracts/idocumentinfo/property_names/). |
| [size](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/size/) | La taille du document en octets. |

### Exemple

```python
from groupdocs.conversion import Converter

def show_document_info(path):
    with Converter(path) as converter:
        info = converter.get_document_info()
        print("Format:", info.format)
        print("Pages count:", info.pages_count)
        print("Creation date:", info.creation_date)
        print("Size (bytes):", info.size)

# Exemple d'utilisation
show_document_info("./lorem-ipsum.txt")
```

### Voir aussi
* module [`groupdocs.conversion.contracts`](/conversion/python-net/groupdocs.conversion.contracts/)
