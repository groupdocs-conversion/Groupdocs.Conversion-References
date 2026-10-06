---
title: "свойство font_info_substitution_enabled"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Флаг, который включает автоматическую замену отсутствующих шрифтов на основе FontInfo в документе."
type: docs
url: /ru/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_info_substitution_enabled/
is_root: false
weight: 2120
---


## font_info_substitution_enabled property

Флаг, включающий автоматическую замену отсутствующих шрифтов на основе FontInfo в документе. По умолчанию: False.

Примечание: порядок замены следующий:
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

### См. также
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
