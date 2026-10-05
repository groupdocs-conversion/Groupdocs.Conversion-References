---
title: "properti font_name_substitution_enabled"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Properti ini menunjukkan apakah font yang hilang secara otomatis diganti berdasarkan nama font."
type: docs
url: /id/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_name_substitution_enabled/
is_root: false
weight: 2130
---


## font_name_substitution_enabled property

Properti ini menunjukkan apakah font yang hilang secara otomatis disubstitusi berdasarkan nama font. Default: False.

Catatan: Urutan substitusi adalah sebagai berikut:

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

### Lihat Juga
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
