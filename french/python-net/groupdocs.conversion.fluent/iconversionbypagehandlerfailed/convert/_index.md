---
title: "méthode convert"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Exécute la chaîne de conversion."
type: docs
url: /fr/python-net/groupdocs.conversion.fluent/iconversionbypagehandlerfailed/convert/
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
    converter.convert("./business-plan.pdf", PdfConvertOptions())
```

### Voir aussi
* class [`IConversionByPageHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlerfailed/)
