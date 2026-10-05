---
title: "metode get_document_info"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Mengambil informasi dokumen sumber, termasuk jumlah halaman dan properti lain yang spesifik untuk tipe file."
type: docs
url: /id/python-net/groupdocs.conversion/converter/get_document_info/
is_root: false
weight: 1080
---


## get_document_info

Mengambil informasi dokumen sumber, termasuk jumlah halaman dan properti lain yang spesifik untuk tipe file.

Pelajari lebih lanjut tentang dokumen yang dikonversi – tipe file, jumlah halaman, tanggal pembuatan, dan banyak properti spesifik format lainnya:
- How to get document info (https://docs.groupdocs.com/display/conversionnet/Get+document+info)

```python
def get_document_info(self):
    ...
```

**Returns:** Document information as `IDocumentInfo`.

### Contoh

```python
from groupdocs.conversion import Converter

with Converter("document.pdf") as converter:
    info = converter.get_document_info()
    print(f"Pages: {info.pages_count}, Format: {info.format}")
```

### Lihat Juga
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
