---
title: "get_document_info methode"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Haalt informatie op over het bron‑document, inclusief paginatelling en andere eigenschappen die specifiek zijn voor het bestandstype."
type: docs
url: /nl/python-net/groupdocs.conversion.fluent/iconversiongetdocumentinfo/get_document_info/
is_root: false
weight: 1010
---


## get_document_info

Haalt informatie op over het bron‑document, inclusief paginatelling en andere eigenschappen die specifiek zijn voor het bestandstype.

```python
def get_document_info(self):
    ...
```

### Voorbeeld

```python
from groupdocs.conversion import Converter

with Converter("document.pdf") as converter:
    info = converter.get_document_info()
    print(f"Pages: {info.pages_count}, Format: {info.format}")
```

### Zie ook
* class [`IConversionGetDocumentInfo`](/conversion/python-net/groupdocs.conversion.fluent/iconversiongetdocumentinfo/)
