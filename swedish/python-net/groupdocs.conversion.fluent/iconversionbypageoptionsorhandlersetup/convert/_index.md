---
title: "convert‑metod"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Utför konverteringskedjan."
type: docs
url: /sv/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/convert/
is_root: false
weight: 1030
---


## convert

Utför konverteringskedjan.

```python
def convert(self):
    ...
```

### Exempel

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_document():
    # Öppna källdokumentet
    with Converter("./business-plan.docx") as converter:
        # Definiera konverteringsalternativ för PDF-utdata
        pdf_options = PdfConvertOptions()
        # Utför konverteringen och spara resultatet
        converter.convert("./business-plan.pdf", pdf_options)

if __name__ == "__main__":
    convert_document()
```

### Se även
* class [`IConversionByPageOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/)
