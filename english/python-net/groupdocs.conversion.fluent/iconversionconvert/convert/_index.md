---
title: convert method
second_title: GroupDocs.Conversion for Python via .NET API References
description: "Execute conversion chain."
type: docs
url: /python-net/groupdocs.conversion.fluent/iconversionconvert/convert/
is_root: false
weight: 1010
---


## convert

Execute conversion chain.

```python
def convert(self):
    ...
```

### Example

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

### See Also
* class [`IConversionConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvert/)
