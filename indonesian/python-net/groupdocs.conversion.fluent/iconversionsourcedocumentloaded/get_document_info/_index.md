---
title: "metode get_document_info"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Mengambil informasi dokumen sumber, termasuk jumlah halaman dan properti lain yang spesifik untuk tipe file."
type: docs
url: /id/python-net/groupdocs.conversion.fluent/iconversionsourcedocumentloaded/get_document_info/
is_root: false
weight: 1070
---


## get_document_info

Mengambil informasi dokumen sumber, termasuk jumlah halaman dan properti lain yang spesifik untuk tipe file.

```python
def get_document_info(self):
    ...
```

**Returns:** DocumentInfo: An object containing details such as format, pages count, creation date, size, and other type‑specific attributes.

### Contoh

```python
from groupdocs.conversion import Converter

with Converter("document.pdf") as converter:
    info = converter.get_document_info()
    print(f"Pages: {info.pages_count}, Format: {info.format}")
```

### Lihat Juga
* class [`IConversionSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsourcedocumentloaded/)
