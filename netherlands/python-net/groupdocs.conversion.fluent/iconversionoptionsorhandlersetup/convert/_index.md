---
title: "convert-methode"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Voer conversieketen uit."
type: docs
url: /nl/python-net/groupdocs.conversion.fluent/iconversionoptionsorhandlersetup/convert/
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

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

### Zie ook
* class [`IConversionOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionoptionsorhandlersetup/)
