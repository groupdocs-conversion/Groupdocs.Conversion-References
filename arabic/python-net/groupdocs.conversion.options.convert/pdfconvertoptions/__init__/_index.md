---
title: "منشئ __init__"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "يُنشئ مثيلًا جديدًا من PdfConvertOptions."
type: docs
url: /ar/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/__init__/
is_root: false
weight: 10
---


## __init__

يُنشئ مثلاً جديداً من [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/).

```python
def __init__(self):
    ...
```

### مثال

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### انظر أيضًا
* class [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/)
