---
title: "método convert"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Ejecuta la cadena de conversión."
type: docs
url: /es/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/convert/
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
    converter.convert("./business-plan.pdf", PdfConvertOptions())
```

### Ver también
* class [`IConversionHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/)
