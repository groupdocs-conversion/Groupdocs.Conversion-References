---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "एक नया ImageConvertOptions इंस्टेंस प्रारंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.conversion.options.convert/imageconvertoptions/__init__/
is_root: false
weight: 10
---


## __init__

एक नया ImageConvertOptions इंस्टेंस प्रारंभ करता है।

```python
def __init__(self):
    ...
```

### उदाहरण

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

### साथ ही देखें
* class [`ImageConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/)
