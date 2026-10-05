---
title: "convert Methode"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Führt die Konvertierungskette aus."
type: docs
url: /de/python-net/groupdocs.conversion.fluent/iconversioncompletedorconvert/convert/
is_root: false
weight: 1030
---


## convert

Führt die Konvertierungskette aus.

```python
def convert(self):
    ...
```

### Beispiel

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

### Siehe auch
* class [`IConversionCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompletedorconvert/)
