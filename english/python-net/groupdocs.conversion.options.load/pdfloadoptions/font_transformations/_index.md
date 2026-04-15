---
title: font_transformations property
second_title: GroupDocs.Conversion for Python via .NET API References
description: 
type: docs
url: /conversion/python-net/groupdocs.conversion.options.load/pdfloadoptions/font_transformations/
is_root: false
weight: 2090
---


## font_transformations property

The font transformations applied after document loading and font substitution are complete, which can modify any fonts in the document, including fonts that were successfully loaded.

Note: Font transformations are applied after all font substitution steps are complete.

Transformations are processed in the order they appear in the list.

Use cases: Styling changes, branding requirements, accessibility improvements.

### Definition:
```python
@property
def font_transformations(self):
    ...
@font_transformations.setter
def font_transformations(self, value):
    ...
```

### See Also
* class [`PdfLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/pdfloadoptions/)
