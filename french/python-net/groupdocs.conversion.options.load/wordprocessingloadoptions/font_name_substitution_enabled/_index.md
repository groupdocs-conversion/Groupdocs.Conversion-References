---
title: "propriété font_name_substitution_enabled"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "La propriété indique si les polices manquantes sont automatiquement substituées en fonction du nom de la police."
type: docs
url: /fr/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_name_substitution_enabled/
is_root: false
weight: 2130
---


## font_name_substitution_enabled property

La propriété indique si les polices manquantes sont automatiquement substituées en fonction du nom de la police. Valeur par défaut : False.

Remarque : l'ordre de substitution est le suivant :

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

### Voir aussi
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
