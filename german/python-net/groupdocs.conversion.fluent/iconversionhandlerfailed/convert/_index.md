---
title: "convert Methode"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Führt die Konvertierungskette aus."
type: docs
url: /de/python-net/groupdocs.conversion.fluent/iconversionhandlerfailed/convert/
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

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### Siehe auch
* class [`IConversionHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlerfailed/)
