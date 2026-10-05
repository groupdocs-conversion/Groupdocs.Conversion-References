---
title: "get_document_info μέθοδος"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Ανακτά πληροφορίες του πηγαίου εγγράφου, συμπεριλαμβανομένου του αριθμού σελίδων και άλλων ιδιοτήτων ειδικών για τον τύπο αρχείου."
type: docs
url: /el/python-net/groupdocs.conversion/converter/get_document_info/
is_root: false
weight: 1080
---


## get_document_info

Ανακτά πληροφορίες του πηγαίου εγγράφου, συμπεριλαμβανομένου του αριθμού σελίδων και άλλων ιδιοτήτων ειδικών για τον τύπο αρχείου.

Μάθετε περισσότερα για το μετατρεπόμενο έγγραφο – τύπο αρχείου, αριθμό σελίδων, ημερομηνία δημιουργίας και πολλές άλλες ιδιότητες ειδικές για τη μορφή:
- How to get document info (https://docs.groupdocs.com/display/conversionnet/Get+document+info)

```python
def get_document_info(self):
    ...
```

**Returns:** Document information as `IDocumentInfo`.

### Παράδειγμα

```python
from groupdocs.conversion import Converter

with Converter("document.pdf") as converter:
    info = converter.get_document_info()
    print(f"Pages: {info.pages_count}, Format: {info.format}")
```

### Δείτε επίσης
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
