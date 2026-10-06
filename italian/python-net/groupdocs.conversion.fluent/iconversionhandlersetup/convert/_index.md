---
title: "metodo convert"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Esegue la catena di conversione."
type: docs
url: /it/python-net/groupdocs.conversion.fluent/iconversionhandlersetup/convert/
is_root: false
weight: 1030
---


## convert

Esegue la catena di conversione.

```python
def convert(self):
    ...
```

### Esempio

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("./business-plan.docx") as converter:
    pdf_options = PdfConvertOptions()
    converter.convert("./business-plan.pdf", pdf_options)
```

### Vedi anche
* class [`IConversionHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersetup/)
