---
title: "convert‑metod"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Utför konverteringskedjan."
type: docs
url: /sv/python-net/groupdocs.conversion.fluent/iconversionconvert/convert/
is_root: false
weight: 1010
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

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

### Se även
* class [`IConversionConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvert/)
