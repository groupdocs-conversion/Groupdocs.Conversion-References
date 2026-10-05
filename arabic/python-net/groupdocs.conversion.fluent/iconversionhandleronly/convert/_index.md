---
title: "طريقة التحويل."
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "نفّذ سلسلة التحويل."
type: docs
url: /ar/python-net/groupdocs.conversion.fluent/iconversionhandleronly/convert/
is_root: false
weight: 1030
---


## convert

نفّذ سلسلة التحويل.

```python
def convert(self):
    ...
```

### مثال

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

### انظر أيضًا
* class [`IConversionHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandleronly/)
