---
title: "__init__ yapıcı"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Yeni bir PdfConvertOptions örneğini başlatır."
type: docs
url: /tr/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/__init__/
is_root: false
weight: 10
---


## __init__

Yeni bir [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/) örneğini başlatır.

```python
def __init__(self):
    ...
```

### Örnek

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### Ayrıca Bakınız
* class [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/)
