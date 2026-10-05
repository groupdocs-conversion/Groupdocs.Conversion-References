---
title: "get_document_info μέθοδος"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Ανακτά πληροφορίες του πηγαίου εγγράφου, συμπεριλαμβανομένου του αριθμού σελίδων και άλλων ιδιοτήτων ειδικών για τον τύπο αρχείου."
type: docs
url: /el/python-net/groupdocs.conversion.fluent/iconversionsourcedocumentloaded/get_document_info/
is_root: false
weight: 1070
---


## get_document_info

Ανακτά πληροφορίες του πηγαίου εγγράφου, συμπεριλαμβανομένου του αριθμού σελίδων και άλλων ιδιοτήτων ειδικών για τον τύπο αρχείου.

```python
def get_document_info(self):
    ...
```

**Returns:** DocumentInfo: An object containing details such as format, pages count, creation date, size, and other type‑specific attributes.

### Παράδειγμα

```python
from groupdocs.conversion import Converter

with Converter("document.pdf") as converter:
    info = converter.get_document_info()
    print(f"Pages: {info.pages_count}, Format: {info.format}")
```

### Δείτε επίσης
* class [`IConversionSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsourcedocumentloaded/)
