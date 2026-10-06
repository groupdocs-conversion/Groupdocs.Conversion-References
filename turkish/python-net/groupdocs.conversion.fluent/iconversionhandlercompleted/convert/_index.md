---
title: "convert yöntemi"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Dönüştürme zincirini yürüt."
type: docs
url: /tr/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/convert/
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

with Converter("./business-plan.docx") as converter:
    converter.convert("./business-plan.pdf", PdfConvertOptions())
```

### Ayrıca Bakınız
* class [`IConversionHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/)
