---
title: "font_name_substitution_enabled eigenschap"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "De eigenschap geeft aan of ontbrekende lettertypen automatisch worden vervangen op basis van de lettertype‑naam."
type: docs
url: /nl/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_name_substitution_enabled/
is_root: false
weight: 2130
---


## font_name_substitution_enabled property

De eigenschap geeft aan of ontbrekende lettertypen automatisch worden vervangen op basis van de lettertype‑naam. Standaard: False.

Opmerking: De volgorde van vervanging is als volgt:

- Automatically substitute missing fonts based on font name (if enabled).
- Automatically substitute missing fonts based on FontConfig (if enabled).
- Substitute missing fonts based on FontSubstitutes (if set).
- Automatically substitute missing fonts based on FontInfo (if enabled).
- Substitute missing fonts based on DefaultFont (if set).

### Definition:
```python
@property
def font_name_substitution_enabled(self):
    ...
@font_name_substitution_enabled.setter
def font_name_substitution_enabled(self, value):
    ...
```

### Zie ook
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
