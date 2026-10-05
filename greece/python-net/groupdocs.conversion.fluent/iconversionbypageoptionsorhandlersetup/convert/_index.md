---
title: "μέθοδος convert"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Εκτελεί την αλυσίδα μετατροπής."
type: docs
url: /el/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/convert/
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

def convert_document():
    # Ανοίξτε το πηγαίο έγγραφο
    with Converter("./business-plan.docx") as converter:
        # Ορίστε τις επιλογές μετατροπής για έξοδο PDF
        pdf_options = PdfConvertOptions()
        # Εκτελέστε τη μετατροπή και αποθηκεύστε το αποτέλεσμα
        converter.convert("./business-plan.pdf", pdf_options)

if __name__ == "__main__":
    convert_document()
```

### Δείτε επίσης
* class [`IConversionByPageOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/)
