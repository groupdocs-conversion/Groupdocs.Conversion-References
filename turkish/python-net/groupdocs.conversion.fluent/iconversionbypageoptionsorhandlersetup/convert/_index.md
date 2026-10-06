---
title: "convert yöntemi"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Dönüşüm zincirini yürütür."
type: docs
url: /tr/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/convert/
is_root: false
weight: 1030
---


## convert

Dönüşüm zincirini yürütür.

```python
def convert(self):
    ...
```

### Örnek

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_document():
    # Kaynak belgeyi aç
    with Converter("./business-plan.docx") as converter:
        # PDF çıktısı için dönüşüm seçeneklerini tanımla
        pdf_options = PdfConvertOptions()
        # Dönüşümü gerçekleştir ve sonucu kaydet
        converter.convert("./business-plan.pdf", pdf_options)

if __name__ == "__main__":
    convert_document()
```

### Ayrıca Bakınız
* class [`IConversionByPageOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/)
