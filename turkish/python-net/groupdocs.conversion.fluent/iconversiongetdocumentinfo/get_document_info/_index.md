---
title: "get_document_info yöntemi"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Kaynak belge bilgilerini alır, sayfa sayısı ve dosya türüne özgü diğer özellikler dahil."
type: docs
url: /tr/python-net/groupdocs.conversion.fluent/iconversiongetdocumentinfo/get_document_info/
is_root: false
weight: 1010
---


## get_document_info

Kaynak belge bilgilerini alır, sayfa sayısı ve dosya türüne özgü diğer özellikler dahil.

```python
def get_document_info(self):
    ...
```

### Örnek

```python
from groupdocs.conversion import Converter

with Converter("document.pdf") as converter:
    info = converter.get_document_info()
    print(f"Pages: {info.pages_count}, Format: {info.format}")
```

### Ayrıca Bakınız
* class [`IConversionGetDocumentInfo`](/conversion/python-net/groupdocs.conversion.fluent/iconversiongetdocumentinfo/)
