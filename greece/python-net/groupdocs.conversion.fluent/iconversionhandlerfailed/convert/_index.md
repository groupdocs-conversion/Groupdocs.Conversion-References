---
title: "μέθοδος convert"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Εκτελεί την αλυσίδα μετατροπής."
type: docs
url: /el/python-net/groupdocs.conversion.fluent/iconversionhandlerfailed/convert/
is_root: false
weight: 1030
---


## convert

Εκτελεί την αλυσίδα μετατροπής.

```python
def convert(self):
    ...
```

### Παράδειγμα

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### Δείτε επίσης
* class [`IConversionHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlerfailed/)
