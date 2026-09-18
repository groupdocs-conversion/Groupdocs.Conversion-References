---
title: min_resolution property
second_title: GroupDocs.Conversion for Python via .NET API References
description: "The per-axis lower bound applied to the capped render DPI when ImageConvertOptions.CapResolutionToPageContent is enabled."
type: docs
url: /python-net/groupdocs.conversion.options.convert/imageconvertoptions/min_resolution/
is_root: false
weight: 2130
---


## min_resolution property

The per-axis lower bound applied to the capped render DPI when [`ImageConvertOptions.CapResolutionToPageContent`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/cap_resolution_to_page_content/) is enabled.

The capped DPI is never lowered below this value. The default is 0 (no floor).

### Definition:
```python
@property
def min_resolution(self):
    ...
@min_resolution.setter
def min_resolution(self, value):
    ...
```

### See Also
* class [`ImageConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/)
