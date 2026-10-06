---
title: "convert yöntemi"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Dönüştürme zincirini yürüt."
type: docs
url: /tr/python-net/groupdocs.conversion.fluent/iconversioncompletedorconvert/convert/
is_root: false
weight: 1030
---


## convert

Dönüştürme zincirini yürüt.

```python
def convert(self):
    ...
```

### Örnek

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

### Ayrıca Bakınız
* class [`IConversionCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompletedorconvert/)
