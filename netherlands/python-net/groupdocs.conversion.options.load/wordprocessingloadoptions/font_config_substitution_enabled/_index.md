---
title: "font_config_substitution_enabled eigenschap"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "De eigenschap schakelt automatische substitutie van ontbrekende lettertypen in op basis van de systeem FontConfig."
type: docs
url: /nl/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_config_substitution_enabled/
is_root: false
weight: 2110
---


## font_config_substitution_enabled property

De eigenschap schakelt automatische vervanging van ontbrekende lettertypen in op basis van de systeem‑FontConfig. Standaard is False.

Opmerking: De volgorde van vervanging is als volgt:
- Automatically substitute missing fonts based on font name (if enabled).
- Automatically substitute missing fonts based on FontConfig (if enabled).
- Substitute missing fonts based on FontSubstitutes (if set).
- Automatically substitute missing fonts based on FontInfo (if enabled).
- Substitute missing fonts based on DefaultFont (if set).

### Definition:
```python
@property
def font_config_substitution_enabled(self):
    ...
@font_config_substitution_enabled.setter
def font_config_substitution_enabled(self, value):
    ...
```

### Zie ook
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
