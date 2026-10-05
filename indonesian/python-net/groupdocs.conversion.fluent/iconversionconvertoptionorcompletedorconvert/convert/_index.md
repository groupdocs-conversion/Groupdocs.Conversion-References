---
title: "metode convert"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Jalankan rantai konversi."
type: docs
url: /id/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorcompletedorconvert/convert/
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

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

### Lihat Juga
* class [`IConversionConvertOptionOrCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorcompletedorconvert/)
