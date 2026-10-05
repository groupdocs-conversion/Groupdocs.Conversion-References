---
title: "metode convert"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Jalankan rantai konversi."
type: docs
url: /id/python-net/groupdocs.conversion.fluent/iconversionbypagehandlerfailed/convert/
is_root: false
weight: 1030
---


## convert

Jalankan rantai konversi.

```python
def convert(self):
    ...
```

### Contoh

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("./business-plan.docx") as converter:
    converter.convert("./business-plan.pdf", PdfConvertOptions())
```

### Lihat Juga
* class [`IConversionByPageHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlerfailed/)
