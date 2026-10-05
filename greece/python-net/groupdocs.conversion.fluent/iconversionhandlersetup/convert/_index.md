---
title: "μέθοδος convert"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Εκτελεί την αλυσίδα μετατροπής."
type: docs
url: /el/python-net/groupdocs.conversion.fluent/iconversionhandlersetup/convert/
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

with Converter("./business-plan.docx") as converter:
    pdf_options = PdfConvertOptions()
    converter.convert("./business-plan.pdf", pdf_options)
```

### Δείτε επίσης
* class [`IConversionHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersetup/)
