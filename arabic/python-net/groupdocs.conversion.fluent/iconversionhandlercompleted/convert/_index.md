---
title: "طريقة التحويل."
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "نفّذ سلسلة التحويل."
type: docs
url: /ar/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/convert/
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

with Converter("./business-plan.docx") as converter:
    converter.convert("./business-plan.pdf", PdfConvertOptions())
```

### انظر أيضًا
* class [`IConversionHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/)
