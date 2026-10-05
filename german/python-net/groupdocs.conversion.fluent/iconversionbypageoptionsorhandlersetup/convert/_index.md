---
title: "convert Methode"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Führt die Konvertierungskette aus."
type: docs
url: /de/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/convert/
is_root: false
weight: 1030
---


## convert

Führt die Konvertierungskette aus.

```python
def convert(self):
    ...
```

### Beispiel

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_document():
    # Öffnen Sie das Quell-Dokument
    with Converter("./business-plan.docx") as converter:
        # Definieren Sie Konvertierungsoptionen für die PDF-Ausgabe
        pdf_options = PdfConvertOptions()
        # Führen Sie die Konvertierung durch und speichern Sie das Ergebnis
        converter.convert("./business-plan.pdf", pdf_options)

if __name__ == "__main__":
    convert_document()
```

### Siehe auch
* class [`IConversionByPageOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/)
