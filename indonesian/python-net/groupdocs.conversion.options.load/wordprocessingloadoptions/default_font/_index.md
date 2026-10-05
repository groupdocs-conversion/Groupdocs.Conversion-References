---
title: "properti default_font"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Font default untuk dokumen WordProcessing."
type: docs
url: /id/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/default_font/
is_root: false
weight: 2080
---


## default_font property

Font default untuk dokumen WordProcessing.

Catatan: Urutan substitusi adalah sebagai berikut:
- Automatically substitute missing fonts based on font name (if enabled).
- Automatically substitute missing fonts based on FontConfig (if enabled).
- Substitute missing fonts based on FontSubstitutes (if set).
- Automatically substitute missing fonts based on FontInfo (if enabled).
- Substitute missing fonts based on DefaultFont (if set).

### Definition:
```python
@property
def default_font(self):
    ...
@default_font.setter
def default_font(self, value):
    ...
```

### Lihat Juga
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
