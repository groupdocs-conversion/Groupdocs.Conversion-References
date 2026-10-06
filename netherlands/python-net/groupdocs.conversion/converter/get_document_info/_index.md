---
title: "get_document_info methode"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Haalt de informatie van het brondocument op, inclusief paginatelling en andere eigenschappen die specifiek zijn voor het bestandstype."
type: docs
url: /nl/python-net/groupdocs.conversion/converter/get_document_info/
is_root: false
weight: 1080
---


## get_document_info

Haalt de informatie van het brondocument op, inclusief paginatelling en andere eigenschappen die specifiek zijn voor het bestandstype.

Meer informatie over het geconverteerde document – bestandstype, paginatelling, aanmaakdatum en vele andere formatspecifieke eigenschappen:
- How to get document info (https://docs.groupdocs.com/display/conversionnet/Get+document+info)

```python
def get_document_info(self):
    ...
```

**Returns:** Document information as `IDocumentInfo`.

### Voorbeeld

```python
from groupdocs.conversion import Converter

with Converter("document.pdf") as converter:
    info = converter.get_document_info()
    print(f"Pages: {info.pages_count}, Format: {info.format}")
```

### Zie ook
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
