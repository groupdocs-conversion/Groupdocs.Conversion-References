---
title: "DocumentInfo sınıfı"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Polimorfik belge bilgilerini almak için temel uygulama."
type: docs
url: /tr/python-net/groupdocs.conversion.contracts/documentinfo/
is_root: false
weight: 120
---


## DocumentInfo class

Polimorfik belge bilgilerini almak için temel uygulama.

Örnekler `Converter.get_document_info()` tarafından döndürülür ve format, sayfa sayısı, oluşturulma tarihi, boyut ve format‑özel özellikler gibi üst verileri sunar.

DocumentInfo türü aşağıdaki üyeleri sunar:

### Yöntemler
| Yöntem | Açıklama |
| :- | :- |
| [get](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/get/) |  |
| [get_file](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/get_file/) |  |
| [get_string](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/get_string/) |  |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [creation_date](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/creation_date/) | Belgenin oluşturulma tarihi. |
| [format](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/format/) | Belgenin formatı. |
| [pages_count](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/pages_count/) | Belgedeki toplam sayfa sayısı. |
| [property_names](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/property_names/) | Bu özellik [`IDocumentInfo.property_names`](/conversion/python-net/groupdocs.conversion.contracts/idocumentinfo/property_names/) uygular. |
| [size](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/size/) | Belgenin bayt cinsinden boyutu. |

### Örnek

```python
from groupdocs.conversion import Converter

def show_document_info(path):
    with Converter(path) as converter:
        info = converter.get_document_info()
        print("Format:", info.format)
        print("Pages count:", info.pages_count)
        print("Creation date:", info.creation_date)
        print("Size (bytes):", info.size)

# Örnek kullanım
show_document_info("./lorem-ipsum.txt")
```

### Ayrıca Bakınız
* module [`groupdocs.conversion.contracts`](/conversion/python-net/groupdocs.conversion.contracts/)
