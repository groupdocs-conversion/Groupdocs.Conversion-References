---
title: "propriété font_info_substitution_enabled"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Le drapeau qui active la substitution automatique des polices manquantes basée sur FontInfo dans le document."
type: docs
url: /fr/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_info_substitution_enabled/
is_root: false
weight: 2120
---


## font_info_substitution_enabled property

Le drapeau qui active la substitution automatique des polices manquantes basée sur FontInfo dans le document. Valeur par défaut : False.

Remarque : l'ordre de substitution est le suivant :
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

### Voir aussi
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
