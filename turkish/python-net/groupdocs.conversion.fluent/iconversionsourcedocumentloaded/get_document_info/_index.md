---
title: "get_document_info yöntemi"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Kaynak belge bilgilerini alır, sayfa sayısı ve dosya türüne özgü diğer özellikler dahil."
type: docs
url: /tr/python-net/groupdocs.conversion.fluent/iconversionsourcedocumentloaded/get_document_info/
is_root: false
weight: 1070
---


## get_document_info

Kaynak belge bilgilerini alır, sayfa sayısı ve dosya türüne özgü diğer özellikler dahil.

```python
def get_document_info(self):
    ...
```

**Returns:** DocumentInfo: An object containing details such as format, pages count, creation date, size, and other type‑specific attributes.

### Örnek

```python
from groupdocs.conversion import Converter

with Converter("document.pdf") as converter:
    info = converter.get_document_info()
    print(f"Pages: {info.pages_count}, Format: {info.format}")
```

### Ayrıca Bakınız
* class [`IConversionSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsourcedocumentloaded/)
