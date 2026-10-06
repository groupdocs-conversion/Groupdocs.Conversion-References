---
title: "convert-methode"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Voert de conversieketen uit."
type: docs
url: /nl/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/convert/
is_root: false
weight: 1030
---


## convert

Voert de conversieketen uit.

```python
def convert(self):
    ...
```

### Voorbeeld

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_document():
    # Open het brondocument
    with Converter("./business-plan.docx") as converter:
        # Definieer conversie‑opties voor PDF-uitvoer
        pdf_options = PdfConvertOptions()
        # Voer de conversie uit en sla het resultaat op
        converter.convert("./business-plan.pdf", pdf_options)

if __name__ == "__main__":
    convert_document()
```

### Zie ook
* class [`IConversionByPageOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/)
