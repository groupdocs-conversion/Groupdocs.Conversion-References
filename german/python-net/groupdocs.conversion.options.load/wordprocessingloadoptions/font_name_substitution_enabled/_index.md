---
title: "font_name_substitution_enabled-Eigenschaft"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Die Eigenschaft gibt an, ob fehlende Schriften basierend auf dem Schriftnamen automatisch substituiert werden."
type: docs
url: /de/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_name_substitution_enabled/
is_root: false
weight: 2130
---


## font_name_substitution_enabled property

Die keep_date_field_original_value‑Eigenschaft gibt an, ob fehlende Schriften automatisch basierend auf dem Schriftnamen substituiert werden. Standard: False.

Hinweis: Die Reihenfolge der Substitution ist wie folgt:

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

### Siehe auch
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
