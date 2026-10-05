---
title: "DocumentInfo Klasse"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Die Basisimplementierung zum Abrufen polymorpher Dokumentinformationen."
type: docs
url: /de/python-net/groupdocs.conversion.contracts/documentinfo/
is_root: false
weight: 120
---


## DocumentInfo class

Die Basisimplementierung zum Abrufen polymorpher Dokumentinformationen.

Instanzen werden von `Converter.get_document_info()` zurückgegeben und stellen Metadaten wie Format, Seitenanzahl, Erstellungsdatum, Größe und format‑spezifische Attribute bereit.

Der DocumentInfo Typ stellt die folgenden Mitglieder bereit:

### Methoden
| Methode | Beschreibung |
| :- | :- |
| [get](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/get/) |  |
| [get_file](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/get_file/) |  |
| [get_string](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/get_string/) |  |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [creation_date](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/creation_date/) | Das Erstellungsdatum des Dokuments. |
| [format](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/format/) | Das Format des Dokuments. |
| [pages_count](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/pages_count/) | Die Gesamtzahl der Seiten im Dokument. |
| [property_names](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/property_names/) | Die Eigenschaft implementiert [`IDocumentInfo.property_names`](/conversion/python-net/groupdocs.conversion.contracts/idocumentinfo/property_names/). |
| [size](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/size/) | Die Größe des Dokuments in Bytes. |

### Beispiel

```python
from groupdocs.conversion import Converter

def show_document_info(path):
    with Converter(path) as converter:
        info = converter.get_document_info()
        print("Format:", info.format)
        print("Pages count:", info.pages_count)
        print("Creation date:", info.creation_date)
        print("Size (bytes):", info.size)

# Beispielhafte Verwendung
show_document_info("./lorem-ipsum.txt")
```

### Siehe auch
* module [`groupdocs.conversion.contracts`](/conversion/python-net/groupdocs.conversion.contracts/)
