---
title: "get_document_info metod"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Hämtar information om källdokumentet, inklusive sidantal och andra egenskaper som är specifika för filtypen."
type: docs
url: /sv/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/get_document_info/
is_root: false
weight: 1070
---


## get_document_info

Hämtar information om källdokumentet, inklusive sidantal och andra egenskaper som är specifika för filtypen.

```python
def get_document_info(self):
    ...
```

**Returns:** DocumentInfo: An object containing details about the source document, such as format, page count, creation date, size, and type‑specific properties.

### Exempel

```python
from groupdocs.conversion import Converter

with Converter("document.pdf") as converter:
    info = converter.get_document_info()
    print(f"Pages: {info.pages_count}, Format: {info.format}")
```

### Se även
* class [`IConversionLoadOptionsOrSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/)
