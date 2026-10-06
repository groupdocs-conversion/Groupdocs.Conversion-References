---
title: "propiedad font_config_substitution_enabled"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "La propiedad habilita la sustitución automática de fuentes faltantes basada en el FontConfig del sistema."
type: docs
url: /es/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_config_substitution_enabled/
is_root: false
weight: 2110
---


## font_config_substitution_enabled property

La propiedad habilita la sustitución automática de fuentes faltantes basada en el FontConfig del sistema. El valor predeterminado es False.

Nota: El orden de sustitución es el siguiente:
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

### Ver también
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
