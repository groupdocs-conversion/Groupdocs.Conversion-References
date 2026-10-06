---
title: "default_font eigenschap"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Het standaardlettertype voor een WordProcessing‑document."
type: docs
url: /nl/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/default_font/
is_root: false
weight: 2080
---


## default_font property

Het standaardlettertype voor een WordProcessing‑document.

Opmerking: De volgorde van vervanging is als volgt:
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

### Zie ook
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
