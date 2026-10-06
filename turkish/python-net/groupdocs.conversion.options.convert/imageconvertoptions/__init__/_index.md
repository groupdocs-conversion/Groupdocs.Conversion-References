---
title: "__init__ yapıcı"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Yeni bir ImageConvertOptions örneği başlatır."
type: docs
url: /tr/python-net/groupdocs.conversion.options.convert/imageconvertoptions/__init__/
is_root: false
weight: 10
---


## __init__

Yeni bir ImageConvertOptions örneği başlatır.

```python
def __init__(self):
    ...
```

### Örnek

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

### Ayrıca Bakınız
* class [`ImageConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/)
