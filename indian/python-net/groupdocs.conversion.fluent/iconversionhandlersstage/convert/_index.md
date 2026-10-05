---
title: "convert विधि"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "परिवर्तन श्रृंखला को निष्पादित करें।"
type: docs
url: /hi/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/convert/
is_root: false
weight: 1030
---


## convert

परिवर्तन श्रृंखला को निष्पादित करें।

```python
def convert(self):
    ...
```

### उदाहरण

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

### साथ ही देखें
* class [`IConversionHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/)
