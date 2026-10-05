---
title: "μέθοδος convert"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Εκτελεί την αλυσίδα μετατροπής."
type: docs
url: /el/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompletedorconvert/convert/
is_root: false
weight: 1010
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

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

### Δείτε επίσης
* class [`IConversionCompressResultCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompletedorconvert/)
