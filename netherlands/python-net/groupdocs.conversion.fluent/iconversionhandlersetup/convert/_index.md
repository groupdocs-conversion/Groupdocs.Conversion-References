---
title: "convert-methode"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Voert de conversieketen uit."
type: docs
url: /nl/python-net/groupdocs.conversion.fluent/iconversionhandlersetup/convert/
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

with Converter("./business-plan.docx") as converter:
    pdf_options = PdfConvertOptions()
    converter.convert("./business-plan.pdf", pdf_options)
```

### Zie ook
* class [`IConversionHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersetup/)
