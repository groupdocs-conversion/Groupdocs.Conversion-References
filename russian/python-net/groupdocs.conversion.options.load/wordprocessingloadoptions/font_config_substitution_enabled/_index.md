---
title: "свойство font_config_substitution_enabled"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Свойство включает автоматическую замену отсутствующих шрифтов на основе системного FontConfig."
type: docs
url: /ru/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_config_substitution_enabled/
is_root: false
weight: 2110
---


## font_config_substitution_enabled property

Свойство включает автоматическую замену отсутствующих шрифтов на основе системного FontConfig. По умолчанию — False.

Примечание: порядок замены следующий:
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

### См. также
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
