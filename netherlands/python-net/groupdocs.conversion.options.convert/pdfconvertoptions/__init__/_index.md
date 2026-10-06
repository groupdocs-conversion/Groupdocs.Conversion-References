---
title: "__init__-constructor"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Initialiseert een nieuw PdfConvertOptions-exemplaar."
type: docs
url: /nl/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialiseert een nieuw [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/) exemplaar.

```python
def __init__(self):
    ...
```

### Voorbeeld

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### Zie ook
* class [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/)
