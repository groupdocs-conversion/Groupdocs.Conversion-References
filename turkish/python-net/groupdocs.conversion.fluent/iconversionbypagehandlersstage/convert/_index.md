---
title: "convert yöntemi"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Dönüşüm zincirini yürütür."
type: docs
url: /tr/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/convert/
is_root: false
weight: 1030
---


## convert

Dönüşüm zincirini yürütür.

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
* class [`IConversionByPageHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/)
