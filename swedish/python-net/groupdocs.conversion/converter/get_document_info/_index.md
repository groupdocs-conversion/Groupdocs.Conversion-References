---
title: "get_document_info metod"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Hämtar information om källdokumentet, inklusive sidantal och andra egenskaper specifika för filtypen."
type: docs
url: /sv/python-net/groupdocs.conversion/converter/get_document_info/
is_root: false
weight: 1080
---


## get_document_info

Hämtar information om källdokumentet, inklusive sidantal och andra egenskaper specifika för filtypen.

Läs mer om konverterat dokument – filtyp, sidantal, skapandedatum och många andra format‑specifika egenskaper:
- How to get document info (https://docs.groupdocs.com/display/conversionnet/Get+document+info)

```python
def get_document_info(self):
    ...
```

**Returns:** Document information as `IDocumentInfo`.

### Exempel

```python
from groupdocs.conversion import Converter

with Converter("document.pdf") as converter:
    info = converter.get_document_info()
    print(f"Pages: {info.pages_count}, Format: {info.format}")
```

### Se även
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
