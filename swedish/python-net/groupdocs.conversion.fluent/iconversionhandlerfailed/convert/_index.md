---
title: "convert‑metod"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Utför konverteringskedjan."
type: docs
url: /sv/python-net/groupdocs.conversion.fluent/iconversionhandlerfailed/convert/
is_root: false
weight: 1030
---


## convert

Utför konverteringskedjan.

```python
def convert(self):
    ...
```

### Exempel

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### Se även
* class [`IConversionHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlerfailed/)
