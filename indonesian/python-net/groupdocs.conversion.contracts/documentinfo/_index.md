---
title: "kelas DocumentInfo"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Implementasi dasar untuk mengambil informasi dokumen polimorfik."
type: docs
url: /id/python-net/groupdocs.conversion.contracts/documentinfo/
is_root: false
weight: 120
---


## DocumentInfo class

Implementasi dasar untuk mengambil informasi dokumen polimorfik.

Instansi dikembalikan oleh `Converter.get_document_info()` dan menampilkan metadata seperti format, jumlah halaman, tanggal pembuatan, ukuran, dan atribut khusus format.

Tipe DocumentInfo menampilkan anggota-anggota berikut:

### Metode
| Metode | Deskripsi |
| :- | :- |
| [get](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/get/) |  |
| [get_file](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/get_file/) |  |
| [get_string](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/get_string/) |  |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [creation_date](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/creation_date/) | Tanggal pembuatan dokumen. |
| [format](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/format/) | Format dokumen. |
| [pages_count](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/pages_count/) | Jumlah total halaman dalam dokumen. |
| [property_names](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/property_names/) | Properti ini mengimplementasikan [`IDocumentInfo.property_names`](/conversion/python-net/groupdocs.conversion.contracts/idocumentinfo/property_names/). |
| [size](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/size/) | Ukuran dokumen dalam byte. |

### Contoh

```python
from groupdocs.conversion import Converter

def show_document_info(path):
    with Converter(path) as converter:
        info = converter.get_document_info()
        print("Format:", info.format)
        print("Pages count:", info.pages_count)
        print("Creation date:", info.creation_date)
        print("Size (bytes):", info.size)

# Contoh penggunaan
show_document_info("./lorem-ipsum.txt")
```

### Lihat Juga
* module [`groupdocs.conversion.contracts`](/conversion/python-net/groupdocs.conversion.contracts/)
