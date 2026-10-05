---
title: "convert विधि"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "परिवर्तन श्रृंखला को निष्पादित करता है।"
type: docs
url: /hi/python-net/groupdocs.conversion.fluent/iconversionhandlersetup/convert/
is_root: false
weight: 1030
---


## convert

परिवर्तन श्रृंखला को निष्पादित करता है।

```python
def convert(self):
    ...
```

### उदाहरण

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("./business-plan.docx") as converter:
    pdf_options = PdfConvertOptions()
    converter.convert("./business-plan.pdf", pdf_options)
```

### साथ ही देखें
* class [`IConversionHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersetup/)
