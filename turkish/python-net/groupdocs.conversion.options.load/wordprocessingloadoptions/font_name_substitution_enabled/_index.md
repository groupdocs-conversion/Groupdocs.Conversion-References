---
title: "font_name_substitution_enabled özelliği"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Bu özellik, eksik yazı tiplerinin yazı tipi adına göre otomatik olarak değiştirilip değiştirilmeyeceğini gösterir."
type: docs
url: /tr/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_name_substitution_enabled/
is_root: false
weight: 2130
---


## font_name_substitution_enabled property

Bu özellik, eksik yazı tiplerinin yazı tipi adına göre otomatik olarak değiştirilip değiştirilmediğini gösterir. Varsayılan: False.

Not: Değiştirme sırası aşağıdaki gibidir:

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

### Ayrıca Bakınız
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
