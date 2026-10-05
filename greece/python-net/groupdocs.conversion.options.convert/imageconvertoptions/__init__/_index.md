---
title: "κατασκευαστής __init__"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί μια νέα παρουσία του ImageConvertOptions."
type: docs
url: /el/python-net/groupdocs.conversion.options.convert/imageconvertoptions/__init__/
is_root: false
weight: 10
---


## __init__

Αρχικοποιεί μια νέα παρουσία του ImageConvertOptions.

```python
def __init__(self):
    ...
```

### Παράδειγμα

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.filetypes import ImageFileType
from groupdocs.conversion.options.convert import ImageConvertOptions

with Converter("slides.pptx") as converter:
    options = ImageConvertOptions()
    options.format = ImageFileType.PNG
    options.page_number = 1
    options.pages_count = 1
    converter.convert("slide-1.png", options)
```

### Δείτε επίσης
* class [`ImageConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/)
