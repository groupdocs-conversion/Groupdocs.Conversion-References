---
title: "convert-methode"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Voert de conversieketen uit."
type: docs
url: /nl/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/convert/
is_root: false
weight: 1030
---


## convert

Voert de conversieketen uit.

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
* class [`IConversionByPageHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/)
