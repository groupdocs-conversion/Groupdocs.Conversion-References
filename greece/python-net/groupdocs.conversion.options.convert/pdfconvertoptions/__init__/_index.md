---
title: "κατασκευαστής __init__"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί μια νέα παρουσία του PdfConvertOptions."
type: docs
url: /el/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/__init__/
is_root: false
weight: 10
---


## __init__

Δημιουργεί ένα νέο αντικείμενο [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/).

```python
def __init__(self):
    ...
```

### Παράδειγμα

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### Δείτε επίσης
* class [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/)
