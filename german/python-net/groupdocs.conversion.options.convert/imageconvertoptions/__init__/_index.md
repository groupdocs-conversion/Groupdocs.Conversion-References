---
title: "__init__‑Konstruktor"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Initialisiert eine neue ImageConvertOptions-Instanz."
type: docs
url: /de/python-net/groupdocs.conversion.options.convert/imageconvertoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialisiert eine neue ImageConvertOptions-Instanz.

```python
def __init__(self):
    ...
```

### Beispiel

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

### Siehe auch
* class [`ImageConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/)
