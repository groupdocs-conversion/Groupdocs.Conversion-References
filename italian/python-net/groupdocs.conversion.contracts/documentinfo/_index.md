---
title: "classe DocumentInfo"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "L'implementazione di base per il recupero delle informazioni polimorfiche del documento."
type: docs
url: /it/python-net/groupdocs.conversion.contracts/documentinfo/
is_root: false
weight: 120
---


## DocumentInfo class

L'implementazione di base per il recupero delle informazioni polimorfiche del documento.

Le istanze vengono restituite da `Converter.get_document_info()` e espongono metadati come formato, conteggio delle pagine, data di creazione, dimensione e attributi specifici del formato.

Il tipo DocumentInfo espone i seguenti membri:

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [get](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/get/) |  |
| [get_file](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/get_file/) |  |
| [get_string](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/get_string/) |  |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [creation_date](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/creation_date/) | La data di creazione del documento. |
| [format](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/format/) | Il formato del documento. |
| [pages_count](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/pages_count/) | Il numero totale di pagine nel documento. |
| [property_names](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/property_names/) | La proprietà implementa [`IDocumentInfo.property_names`](/conversion/python-net/groupdocs.conversion.contracts/idocumentinfo/property_names/). |
| [size](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/size/) | La dimensione del documento in byte. |

### Esempio

```python
from groupdocs.conversion import Converter

def show_document_info(path):
    with Converter(path) as converter:
        info = converter.get_document_info()
        print("Format:", info.format)
        print("Pages count:", info.pages_count)
        print("Creation date:", info.creation_date)
        print("Size (bytes):", info.size)

# Esempio di utilizzo
show_document_info("./lorem-ipsum.txt")
```

### Vedi anche
* module [`groupdocs.conversion.contracts`](/conversion/python-net/groupdocs.conversion.contracts/)
