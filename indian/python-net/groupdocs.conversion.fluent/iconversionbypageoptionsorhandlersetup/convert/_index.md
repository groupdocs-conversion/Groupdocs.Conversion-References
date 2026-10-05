---
title: "convert विधि"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "परिवर्तन श्रृंखला को निष्पादित करता है।"
type: docs
url: /hi/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/convert/
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

def convert_document():
    # स्रोत दस्तावेज़ खोलें
    with Converter("./business-plan.docx") as converter:
        # PDF आउटपुट के लिए रूपांतरण विकल्प निर्धारित करें
        pdf_options = PdfConvertOptions()
        # रूपांतरण करें और परिणाम सहेजें
        converter.convert("./business-plan.pdf", pdf_options)

if __name__ == "__main__":
    convert_document()
```

### साथ ही देखें
* class [`IConversionByPageOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/)
