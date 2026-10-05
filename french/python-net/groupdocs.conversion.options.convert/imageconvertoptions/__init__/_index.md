---
title: "constructeur __init__"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Initialise une nouvelle instance d'ImageConvertOptions."
type: docs
url: /fr/python-net/groupdocs.conversion.options.convert/imageconvertoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialise une nouvelle instance d'ImageConvertOptions.

```python
def __init__(self):
    ...
```

### Exemple

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

### Voir aussi
* class [`ImageConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/)
