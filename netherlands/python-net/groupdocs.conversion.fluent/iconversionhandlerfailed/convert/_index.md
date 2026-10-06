---
title: "convert-methode"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Voer conversieketen uit."
type: docs
url: /nl/python-net/groupdocs.conversion.fluent/iconversionhandlerfailed/convert/
is_root: false
weight: 1030
---


## convert

Voer conversieketen uit.

```python
def convert(self):
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
* class [`IConversionHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlerfailed/)
