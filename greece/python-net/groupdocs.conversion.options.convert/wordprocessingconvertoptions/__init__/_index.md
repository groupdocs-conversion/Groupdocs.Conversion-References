---
title: "κατασκευαστής __init__"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί ένα νέο στιγμιότυπο του WordProcessingConvertOptions."
type: docs
url: /el/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/__init__/
is_root: false
weight: 10
---


## __init__

Αρχικοποιεί ένα νέο στιγμιότυπο του [`WordProcessingConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/).

```python
def __init__(self):
    ...
```

### Παράδειγμα

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import WordProcessingConvertOptions
from groupdocs.conversion.filetypes import WordProcessingFileType

with Converter("./business-plan.docx") as converter:
    options = WordProcessingConvertOptions()
    options.format = WordProcessingFileType.TXT
    converter.convert("./business-plan.txt", options)
```

### Δείτε επίσης
* class [`WordProcessingConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/)
