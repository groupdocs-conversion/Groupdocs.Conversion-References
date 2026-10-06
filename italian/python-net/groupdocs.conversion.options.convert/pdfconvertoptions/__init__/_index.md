---
title: "costruttore __init__"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Inizializza una nuova istanza di PdfConvertOptions."
type: docs
url: /it/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/__init__/
is_root: false
weight: 10
---


## __init__

Inizializza una nuova istanza di [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/).

```python
def __init__(self):
    ...
```

### Esempio

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### Vedi anche
* class [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/)
