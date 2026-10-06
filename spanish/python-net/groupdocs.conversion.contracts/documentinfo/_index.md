---
title: "Clase DocumentInfo"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "La implementación base para recuperar información polimórfica del documento."
type: docs
url: /es/python-net/groupdocs.conversion.contracts/documentinfo/
is_root: false
weight: 120
---


## DocumentInfo class

La implementación base para recuperar información polimórfica del documento.

Las instancias son devueltas por `Converter.get_document_info()` y exponen metadatos como formato, número de páginas, fecha de creación, tamaño y atributos específicos del formato.

El tipo DocumentInfo expone los siguientes miembros:

### Métodos
| Método | Descripción |
| :- | :- |
| [get](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/get/) |  |
| [get_file](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/get_file/) |  |
| [get_string](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/get_string/) |  |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [creation_date](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/creation_date/) | La fecha de creación del documento. |
| [format](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/format/) | El formato del documento. |
| [pages_count](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/pages_count/) | El número total de páginas del documento. |
| [property_names](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/property_names/) | La propiedad implementa [`IDocumentInfo.property_names`](/conversion/python-net/groupdocs.conversion.contracts/idocumentinfo/property_names/). |
| [size](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/size/) | El tamaño del documento en bytes. |

### Ejemplo

```python
from groupdocs.conversion import Converter

def show_document_info(path):
    with Converter(path) as converter:
        info = converter.get_document_info()
        print("Format:", info.format)
        print("Pages count:", info.pages_count)
        print("Creation date:", info.creation_date)
        print("Size (bytes):", info.size)

# Ejemplo de uso
show_document_info("./lorem-ipsum.txt")
```

### Ver también
* module [`groupdocs.conversion.contracts`](/conversion/python-net/groupdocs.conversion.contracts/)
