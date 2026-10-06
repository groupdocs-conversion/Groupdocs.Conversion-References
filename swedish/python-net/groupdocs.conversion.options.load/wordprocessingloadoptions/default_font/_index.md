---
title: "default_font egenskap"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Standardteckensnittet för ett WordProcessing‑dokument."
type: docs
url: /sv/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/default_font/
is_root: false
weight: 2080
---


## default_font property

Standardteckensnittet för ett WordProcessing‑dokument.

Obs: Ordningen för ersättning är enligt följande:
- Automatically substitute missing fonts based on font name (if enabled).
- Automatically substitute missing fonts based on FontConfig (if enabled).
- Substitute missing fonts based on FontSubstitutes (if set).
- Automatically substitute missing fonts based on FontInfo (if enabled).
- Substitute missing fonts based on DefaultFont (if set).

### Definition:
```python
@property
def default_font(self):
    ...
@default_font.setter
def default_font(self, value):
    ...
```

### Se även
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
