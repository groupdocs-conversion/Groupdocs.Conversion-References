---
title: convert method
second_title: GroupDocs.Conversion for Python via .NET API References
description: "Executes conversion chain."
type: docs
url: /python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/convert/
is_root: false
weight: 1030
---


## convert

Executes conversion chain.

```python
def convert(self):
    ...
```

### Example

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_document():
    # Open the source document
    with Converter("./business-plan.docx") as converter:
        # Define conversion options for PDF output
        pdf_options = PdfConvertOptions()
        # Perform the conversion and save the result
        converter.convert("./business-plan.pdf", pdf_options)

if __name__ == "__main__":
    convert_document()
```

### See Also
* class [`IConversionByPageOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/)
