---
title: "propriété font_substitutes"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Les substituts de police utilisés lors de la conversion d'un document WordProcessing."
type: docs
url: /fr/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_substitutes/
is_root: false
weight: 2140
---


## font_substitutes property

Les substituts de police utilisés lors de la conversion d'un document WordProcessing.

Remarque : l'ordre de substitution est le suivant :

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

### Voir aussi
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
