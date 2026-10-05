---
title: "méthode convert"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Exécute la chaîne de conversion."
type: docs
url: /fr/python-net/groupdocs.conversion.fluent/iconversionhandlersetup/convert/
is_root: false
weight: 1030
---


## convert

Exécute la chaîne de conversion.

```python
def convert(self):
    ...
```

### Exemple

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("./business-plan.docx") as converter:
    pdf_options = PdfConvertOptions()
    converter.convert("./business-plan.pdf", pdf_options)
```

### Voir aussi
* class [`IConversionHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersetup/)
