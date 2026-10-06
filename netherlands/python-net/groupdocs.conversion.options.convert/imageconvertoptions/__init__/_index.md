---
title: "__init__-constructor"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Initialiseert een nieuw ImageConvertOptions‑exemplaar."
type: docs
url: /nl/python-net/groupdocs.conversion.options.convert/imageconvertoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialiseert een nieuw ImageConvertOptions‑exemplaar.

```python
def __init__(self):
    ...
```

### Voorbeeld

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

### Zie ook
* class [`ImageConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/)
