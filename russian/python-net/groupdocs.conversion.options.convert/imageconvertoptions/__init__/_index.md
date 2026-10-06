---
title: "конструктор __init__"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Инициализирует новый экземпляр ImageConvertOptions."
type: docs
url: /ru/python-net/groupdocs.conversion.options.convert/imageconvertoptions/__init__/
is_root: false
weight: 10
---


## __init__

Инициализирует новый экземпляр ImageConvertOptions.

```python
def __init__(self):
    ...
```

### Пример

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

### См. также
* class [`ImageConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/)
