---
title: "metodo convert"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Esegui la catena di conversione."
type: docs
url: /it/python-net/groupdocs.conversion.fluent/iconversionbypagehandlercompleted/convert/
is_root: false
weight: 1030
---


## convert

Esegui la catena di conversione.

```python
def convert(self):
    ...
```

### Esempio

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

### Vedi anche
* class [`IConversionByPageHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlercompleted/)
