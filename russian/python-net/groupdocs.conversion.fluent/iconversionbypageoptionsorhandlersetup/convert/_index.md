---
title: "метод convert"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Выполняет цепочку конвертации."
type: docs
url: /ru/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/convert/
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

def convert_document():
    # Откройте исходный документ
    with Converter("./business-plan.docx") as converter:
        # Определите параметры конвертации для вывода PDF
        pdf_options = PdfConvertOptions()
        # Выполните конвертацию и сохраните результат
        converter.convert("./business-plan.pdf", pdf_options)

if __name__ == "__main__":
    convert_document()
```

### См. также
* class [`IConversionByPageOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/)
