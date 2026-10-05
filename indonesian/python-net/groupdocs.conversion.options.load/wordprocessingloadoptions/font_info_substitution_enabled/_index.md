---
title: "properti font_info_substitution_enabled"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Flag yang memungkinkan substitusi otomatis font yang hilang berdasarkan FontInfo dalam dokumen."
type: docs
url: /id/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_info_substitution_enabled/
is_root: false
weight: 2120
---


## font_info_substitution_enabled property

Flag yang mengaktifkan substitusi otomatis font yang hilang berdasarkan FontInfo dalam dokumen. Default: False.

Catatan: Urutan substitusi adalah sebagai berikut:
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

### Lihat Juga
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
