---
title: "font_substitutes eigenschap"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "De lettertype‑substituten die worden gebruikt bij het converteren van een WordProcessing‑document."
type: docs
url: /nl/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_substitutes/
is_root: false
weight: 2140
---


## font_substitutes property

De lettertype‑substituten die worden gebruikt bij het converteren van een WordProcessing‑document.

Opmerking: De volgorde van vervanging is als volgt:

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

### Zie ook
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
