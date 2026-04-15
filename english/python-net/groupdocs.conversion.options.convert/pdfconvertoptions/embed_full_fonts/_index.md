---
title: embed_full_fonts property
second_title: GroupDocs.Conversion for Python via .NET API References
description: 
type: docs
url: /conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/embed_full_fonts/
is_root: false
weight: 2020
---


## embed_full_fonts property

The full font file is embedded into the PDF instead of a subset when set to True.

This increases the output file size but ensures better compatibility when editing the resulting PDF.

Applies only when converting from WordProcessing documents.

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
