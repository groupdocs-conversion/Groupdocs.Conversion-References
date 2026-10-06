---
title: "font_substitutes egenskap"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Teckensnittsersättningar som används vid konvertering av ett WordProcessing‑dokument."
type: docs
url: /sv/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_substitutes/
is_root: false
weight: 2140
---


## font_substitutes property

Teckensnittsersättningar som används vid konvertering av ett WordProcessing‑dokument.

Obs: Ordningen för ersättning är enligt följande:

- 1) Automatically substitute missing fonts based on font name (if enabled).
- 2) Automatically substitute missing fonts based on FontConfig (if enabled).
- 3) Substitute missing fonts based on FontSubstitutes (if set).
- 4) Automatically substitute missing fonts based on FontInfo (if enabled).
- 5) Substitute missing fonts based on DefaultFont (if set).

### Definition:
```python
@property
def font_substitutes(self):
    ...
@font_substitutes.setter
def font_substitutes(self, value):
    ...
```

### Se även
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
