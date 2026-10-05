---
title: "metode get_document_info"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Mengambil informasi dokumen sumber, termasuk jumlah halaman dan properti lain yang spesifik untuk tipe file."
type: docs
url: /id/python-net/groupdocs.conversion.fluent/iconversiongetdocumentinfo/get_document_info/
is_root: false
weight: 1010
---


## get_document_info

Mengambil informasi dokumen sumber, termasuk jumlah halaman dan properti lain yang spesifik untuk tipe file.

```python
def get_document_info(self):
    ...
```

### Contoh

```python
from groupdocs.conversion import Converter

with Converter("document.pdf") as converter:
    info = converter.get_document_info()
    print(f"Pages: {info.pages_count}, Format: {info.format}")
```

### Lihat Juga
* class [`IConversionGetDocumentInfo`](/conversion/python-net/groupdocs.conversion.fluent/iconversiongetdocumentinfo/)
