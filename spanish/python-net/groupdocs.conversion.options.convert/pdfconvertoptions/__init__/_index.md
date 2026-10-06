---
title: "constructor __init__"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Inicializa una nueva instancia de PdfConvertOptions."
type: docs
url: /es/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/__init__/
is_root: false
weight: 10
---


## __init__

Inicializa una nueva instancia de [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/).

```python
def __init__(self):
    ...
```

### Ejemplo

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### Ver también
* class [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/)
