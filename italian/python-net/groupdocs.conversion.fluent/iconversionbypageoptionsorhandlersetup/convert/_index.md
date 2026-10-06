---
title: "metodo convert"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Esegue la catena di conversione."
type: docs
url: /it/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/convert/
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

def convert_document():
    # Apri il documento di origine
    with Converter("./business-plan.docx") as converter:
        # Definisci le opzioni di conversione per l'output PDF
        pdf_options = PdfConvertOptions()
        # Esegui la conversione e salva il risultato
        converter.convert("./business-plan.pdf", pdf_options)

if __name__ == "__main__":
    convert_document()
```

### Vedi anche
* class [`IConversionByPageOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/)
