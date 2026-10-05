---
title: "get_document_info μέθοδος"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Ανακτά πληροφορίες του πηγαίου εγγράφου, συμπεριλαμβανομένου του αριθμού σελίδων και άλλων ιδιοτήτων ειδικών για τον τύπο αρχείου."
type: docs
url: /el/python-net/groupdocs.conversion.fluent/iconversiongetdocumentinfo/get_document_info/
is_root: false
weight: 1010
---


## get_document_info

Ανακτά πληροφορίες του πηγαίου εγγράφου, συμπεριλαμβανομένου του αριθμού σελίδων και άλλων ιδιοτήτων ειδικών για τον τύπο αρχείου.

```python
def get_document_info(self):
    ...
```

### Παράδειγμα

```python
from groupdocs.conversion import Converter

with Converter("document.pdf") as converter:
    info = converter.get_document_info()
    print(f"Pages: {info.pages_count}, Format: {info.format}")
```

### Δείτε επίσης
* class [`IConversionGetDocumentInfo`](/conversion/python-net/groupdocs.conversion.fluent/iconversiongetdocumentinfo/)
