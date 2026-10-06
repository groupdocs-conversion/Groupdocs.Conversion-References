---
title: "método convert"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Ejecuta la cadena de conversión."
type: docs
url: /es/python-net/groupdocs.conversion.fluent/iconversionhandlersetup/convert/
is_root: false
weight: 1030
---


## convert

Ejecuta la cadena de conversión.

```python
def convert(self):
    ...
```

### Ejemplo

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("./business-plan.docx") as converter:
    pdf_options = PdfConvertOptions()
    converter.convert("./business-plan.pdf", pdf_options)
```

### Ver también
* class [`IConversionHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersetup/)
