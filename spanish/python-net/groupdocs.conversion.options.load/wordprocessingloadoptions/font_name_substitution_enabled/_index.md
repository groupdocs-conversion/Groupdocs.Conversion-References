---
title: "propiedad font_name_substitution_enabled"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "La propiedad indica si las fuentes faltantes se sustituyen automáticamente según el nombre de la fuente."
type: docs
url: /es/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_name_substitution_enabled/
is_root: false
weight: 2130
---


## font_name_substitution_enabled property

La propiedad indica si las fuentes faltantes se sustituyen automáticamente según el nombre de la fuente. Predeterminado: False.

Nota: El orden de sustitución es el siguiente:

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

### Ver también
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
