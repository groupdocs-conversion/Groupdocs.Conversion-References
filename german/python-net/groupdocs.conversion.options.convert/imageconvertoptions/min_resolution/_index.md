---
title: "min_resolution Eigenschaft"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Die pro Achse geltende Untergrenze, die auf die begrenzte Render-DPI angewendet wird, wenn ImageConvertOptions.CapResolutionToPageContent aktiviert ist."
type: docs
url: /de/python-net/groupdocs.conversion.options.convert/imageconvertoptions/min_resolution/
is_root: false
weight: 2130
---


## min_resolution property

Die achsenweise untere Grenze, die auf die begrenzte Render-DPI angewendet wird, wenn [`ImageConvertOptions.CapResolutionToPageContent`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/cap_resolution_to_page_content/) aktiviert ist.

Die begrenzte DPI wird niemals unter diesen Wert gesenkt. Standard ist 0 (keine Untergrenze).

### Definition:
```python
@property
def min_resolution(self):
    ...
@min_resolution.setter
def min_resolution(self, value):
    ...
```

### Siehe auch
* class [`ImageConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/)
