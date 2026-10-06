---
title: "método convert"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Ejecuta la cadena de conversión."
type: docs
url: /es/python-net/groupdocs.conversion.fluent/iconversionconvert/convert/
is_root: false
weight: 1010
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

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

### Ver también
* class [`IConversionConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvert/)
