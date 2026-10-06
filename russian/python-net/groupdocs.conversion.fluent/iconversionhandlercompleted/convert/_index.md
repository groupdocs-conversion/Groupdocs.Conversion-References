---
title: "метод convert"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Выполняет цепочку конвертации."
type: docs
url: /ru/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/convert/
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

with Converter("./business-plan.docx") as converter:
    converter.convert("./business-plan.pdf", PdfConvertOptions())
```

### См. также
* class [`IConversionHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/)
