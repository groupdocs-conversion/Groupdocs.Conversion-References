---
title: "метод convert"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Выполняет цепочку конвертации."
type: docs
url: /ru/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/convert/
is_root: false
weight: 1030
---


## convert

Выполняет цепочку конвертации.

```python
def convert(self):
    ...
```

### Пример

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

### См. также
* class [`IConversionByPageHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/)
