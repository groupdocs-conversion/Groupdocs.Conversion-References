---
title: "font_info_substitution_enabled egenskap"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Flaggan som möjliggör automatisk ersättning av saknade teckensnitt baserat på FontInfo i dokumentet."
type: docs
url: /sv/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_info_substitution_enabled/
is_root: false
weight: 2120
---


## font_info_substitution_enabled property

Flaggan som möjliggör automatisk ersättning av saknade teckensnitt baserat på FontInfo i dokumentet. Standard: False.

Obs: Ordningen för ersättning är enligt följande:
- Automatically substitute missing fonts based on font name (if enabled).
- Automatically substitute missing fonts based on FontConfig (if enabled).
- Substitute missing fonts based on FontSubstitutes (if set).
- Automatically substitute missing fonts based on FontInfo (if enabled).
- Substitute missing fonts based on DefaultFont (if set).

### Definition:
```python
@property
def font_info_substitution_enabled(self):
    ...
@font_info_substitution_enabled.setter
def font_info_substitution_enabled(self, value):
    ...
```

### Se även
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
