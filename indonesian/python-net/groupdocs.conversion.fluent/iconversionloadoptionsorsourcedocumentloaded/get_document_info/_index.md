---
title: "metode get_document_info"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Mengambil informasi dokumen sumber, termasuk jumlah halaman dan properti lain yang spesifik untuk tipe file."
type: docs
url: /id/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/get_document_info/
is_root: false
weight: 1070
---


## get_document_info

Mengambil informasi dokumen sumber, termasuk jumlah halaman dan properti lain yang spesifik untuk tipe file.

```python
def get_document_info(self):
    ...
```

**Returns:** DocumentInfo: An object containing details about the source document, such as format, page count, creation date, size, and type‑specific properties.

### Contoh

```python
from groupdocs.conversion import Converter

with Converter("document.pdf") as converter:
    info = converter.get_document_info()
    print(f"Pages: {info.pages_count}, Format: {info.format}")
```

### Lihat Juga
* class [`IConversionLoadOptionsOrSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/)
