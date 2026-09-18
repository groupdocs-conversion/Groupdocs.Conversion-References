---
title: cap_resolution_to_page_content property
second_title: GroupDocs.Conversion for Python via .NET API References
description: "The property caps the per-page PDF render resolution to the page's native raster resolution, preventing rendering at a higher DPI than the embedded image and emitting the page at its native (smaller)…"
type: docs
url: /python-net/groupdocs.conversion.options.convert/imageconvertoptions/cap_resolution_to_page_content/
is_root: false
weight: 2030
---


## cap_resolution_to_page_content property

The property caps the per-page PDF render resolution to the page's native raster resolution, preventing rendering at a higher DPI than the embedded image and emitting the page at its native (smaller) pixel dimensions and DPI in the final output.

Only image‑dominated (scan) pages are affected; pages with text or vector content are never softened and are emitted at the requested DPI. The cap is ignored when an explicit output [`ImageConvertOptions.Width`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/width/) or [`ImageConvertOptions.Height`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/height/) is set. The default is False (no capping; every page is rendered and emitted at the requested DPI).

### Definition:
```python
@property
def cap_resolution_to_page_content(self):
    ...
@cap_resolution_to_page_content.setter
def cap_resolution_to_page_content(self, value):
    ...
```

### See Also
* class [`ImageConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/)
