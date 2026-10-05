---
title: "__init__‑Konstruktor"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Initialisiert eine neue PdfConvertOptions-Instanz."
type: docs
url: /de/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialisiert eine neue [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/) Instanz.

```python
def __init__(self):
    ...
```

### Beispiel

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### Siehe auch
* class [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/)
