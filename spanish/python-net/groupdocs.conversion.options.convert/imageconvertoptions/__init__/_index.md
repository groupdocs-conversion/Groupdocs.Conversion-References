---
title: "constructor __init__"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Inicializa una nueva instancia de ImageConvertOptions."
type: docs
url: /es/python-net/groupdocs.conversion.options.convert/imageconvertoptions/__init__/
is_root: false
weight: 10
---


## __init__

Inicializa una nueva instancia de ImageConvertOptions.

```python
def __init__(self):
    ...
```

### Ejemplo

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

### Ver también
* class [`ImageConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/)
