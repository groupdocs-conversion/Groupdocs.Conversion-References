---
title: "konstruktor __init__"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Menginisialisasi sebuah instance PdfConvertOptions baru."
type: docs
url: /id/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/__init__/
is_root: false
weight: 10
---


## __init__

Menginisialisasi sebuah instance baru [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/).

```python
def __init__(self):
    ...
```

### Contoh

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### Lihat Juga
* class [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/)
