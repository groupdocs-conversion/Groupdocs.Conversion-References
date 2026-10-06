---
title: "font_info_substitution_enabled özelliği"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Belgedeki FontInfo'a dayalı olarak eksik yazı tiplerinin otomatik olarak değiştirilmesini sağlayan bayrak."
type: docs
url: /tr/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_info_substitution_enabled/
is_root: false
weight: 2120
---


## font_info_substitution_enabled property

Belgedeki FontInfo'a dayalı eksik yazı tiplerinin otomatik olarak değiştirilmesini sağlayan bayrak. Varsayılan: False.

Not: Değiştirme sırası aşağıdaki gibidir:
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

### Ayrıca Bakınız
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
