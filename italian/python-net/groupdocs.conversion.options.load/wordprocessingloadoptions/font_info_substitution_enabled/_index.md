---
title: "font_info_substitution_enabled proprietà"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Il flag che consente la sostituzione automatica dei caratteri mancanti basata su FontInfo nel documento."
type: docs
url: /it/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_info_substitution_enabled/
is_root: false
weight: 2120
---


## font_info_substitution_enabled property

Il flag che abilita la sostituzione automatica dei font mancanti basata su FontInfo nel documento. Predefinito: False.

Nota: L'ordine di sostituzione è il seguente:
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

### Vedi anche
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
