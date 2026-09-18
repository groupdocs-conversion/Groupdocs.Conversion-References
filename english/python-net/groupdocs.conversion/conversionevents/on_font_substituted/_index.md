---
title: on_font_substituted property
second_title: GroupDocs.Conversion for Python via .NET API References
description: "The event fired when a font referenced by the source document is not available and is substituted (either by a customer‑supplied FontSubstitute rule, by the configured default font, or by the…"
type: docs
url: /python-net/groupdocs.conversion/conversionevents/on_font_substituted/
is_root: false
weight: 2070
---


## on_font_substituted property

The event fired when a font referenced by the source document is not available and is substituted (either by a customer‑supplied [`FontSubstitute`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitute/) rule, by the configured default font, or by the conversion pipeline's internal fallback).

The event is deduplicated per `(SourceFileName, OriginalFontName)` within a single `Converter.Convert(...)` call — subscribers receive at most one notification per missing font per source document. Fires synchronously on the conversion thread. Not raised for image conversions.

For presentation documents, font substitution is detected only on Windows, because the engine resolves it through platform‑specific font matching that is unavailable on other operating systems.

### Definition:
```python
@property
def on_font_substituted(self):
    ...
@on_font_substituted.setter
def on_font_substituted(self, value):
    ...
```

### See Also
* class [`ConversionEvents`](/conversion/python-net/groupdocs.conversion/conversionevents/)
