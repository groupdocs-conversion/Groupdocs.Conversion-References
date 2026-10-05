---
title: "طريقة التحويل."
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "ينفّذ سلسلة التحويل."
type: docs
url: /ar/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/convert/
is_root: false
weight: 1030
---


## convert

ينفّذ سلسلة التحويل.

```python
def convert(self):
    ...
```

### مثال

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_document():
    # افتح المستند المصدر
    with Converter("./business-plan.docx") as converter:
        # حدد خيارات التحويل لإخراج PDF
        pdf_options = PdfConvertOptions()
        # نفّذ التحويل واحفظ النتيجة
        converter.convert("./business-plan.pdf", pdf_options)

if __name__ == "__main__":
    convert_document()
```

### انظر أيضًا
* class [`IConversionByPageOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/)
