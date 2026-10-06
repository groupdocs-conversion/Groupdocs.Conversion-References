---
title: "свойство font_name_substitution_enabled"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Это свойство указывает, заменяются ли отсутствующие шрифты автоматически на основе имени шрифта."
type: docs
url: /ru/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_name_substitution_enabled/
is_root: false
weight: 2130
---


## font_name_substitution_enabled property

Свойство указывает, заменяются ли автоматически отсутствующие шрифты на основе имени шрифта. По умолчанию: False.

Примечание: порядок замены следующий:

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

### См. также
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
