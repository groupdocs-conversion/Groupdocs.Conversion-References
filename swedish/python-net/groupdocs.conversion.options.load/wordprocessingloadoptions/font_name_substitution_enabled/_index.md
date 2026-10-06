---
title: "font_name_substitution_enabled egenskap"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Egenskapen indikerar om saknade teckensnitt automatiskt ersätts baserat på teckensnittsnamnet."
type: docs
url: /sv/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_name_substitution_enabled/
is_root: false
weight: 2130
---


## font_name_substitution_enabled property

Egenskapen indikerar om saknade teckensnitt automatiskt ersätts baserat på teckensnittsnamnet. Standard: False.

Obs: Ordningen för ersättning är enligt följande:

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

### Se även
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
