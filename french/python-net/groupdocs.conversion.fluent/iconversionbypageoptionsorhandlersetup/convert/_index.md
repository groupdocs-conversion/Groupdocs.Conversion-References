---
title: "méthode convert"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Exécute la chaîne de conversion."
type: docs
url: /fr/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/convert/
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

def convert_document():
    # Ouvrez le document source
    with Converter("./business-plan.docx") as converter:
        # Définissez les options de conversion pour la sortie PDF
        pdf_options = PdfConvertOptions()
        # Effectuez la conversion et enregistrez le résultat
        converter.convert("./business-plan.pdf", pdf_options)

if __name__ == "__main__":
    convert_document()
```

### Voir aussi
* class [`IConversionByPageOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/)
