---
title: "propiedad font_info_substitution_enabled"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "La bandera que habilita la sustitución automática de fuentes faltantes basada en FontInfo en el documento."
type: docs
url: /es/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_info_substitution_enabled/
is_root: false
weight: 2120
---


## font_info_substitution_enabled property

La bandera que habilita la sustitución automática de fuentes faltantes basada en FontInfo en el documento. Predeterminado: False.

Nota: El orden de sustitución es el siguiente:
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

### Ver también
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
