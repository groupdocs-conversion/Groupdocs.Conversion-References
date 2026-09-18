---
title: embed_full_fonts property
second_title: GroupDocs.Conversion for Python via .NET API References
description: "The property determines whether the full font file is embedded into the PDF instead of a subset."
type: docs
url: /python-net/groupdocs.conversion.options.convert/pdfconvertoptions/embed_full_fonts/
is_root: false
weight: 2020
---


## embed_full_fonts property

The property determines whether the full font file is embedded into the PDF instead of a subset.

When set to True, the output file size increases but ensures better compatibility when editing the resulting PDF. Applies only when converting from WordProcessing documents.

### Definition:
```python
@property
def embed_full_fonts(self):
    ...
@embed_full_fonts.setter
def embed_full_fonts(self, value):
    ...
```

### See Also
* class [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/)
