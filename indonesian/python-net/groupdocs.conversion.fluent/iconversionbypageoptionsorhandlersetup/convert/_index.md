---
title: "metode convert"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Menjalankan rantai konversi."
type: docs
url: /id/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/convert/
is_root: false
weight: 1030
---


## convert

Menjalankan rantai konversi.

```python
def convert(self):
    ...
```

### Contoh

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_document():
    # Buka dokumen sumber
    with Converter("./business-plan.docx") as converter:
        # Tentukan opsi konversi untuk output PDF
        pdf_options = PdfConvertOptions()
        # Lakukan konversi dan simpan hasilnya
        converter.convert("./business-plan.pdf", pdf_options)

if __name__ == "__main__":
    convert_document()
```

### Lihat Juga
* class [`IConversionByPageOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/)
