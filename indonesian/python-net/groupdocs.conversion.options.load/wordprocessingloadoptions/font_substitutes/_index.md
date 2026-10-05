---
title: "properti font_substitutes"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Substitusi font yang digunakan saat mengonversi dokumen WordProcessing."
type: docs
url: /id/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_substitutes/
is_root: false
weight: 2140
---


## font_substitutes property

Substitusi font yang digunakan saat mengonversi dokumen WordProcessing.

Catatan: Urutan substitusi adalah sebagai berikut:

- 1) Automatically substitute missing fonts based on font name (if enabled).
- 2) Automatically substitute missing fonts based on FontConfig (if enabled).
- 3) Substitute missing fonts based on FontSubstitutes (if set).
- 4) Automatically substitute missing fonts based on FontInfo (if enabled).
- 5) Substitute missing fonts based on DefaultFont (if set).

### Definition:
```python
@property
def font_substitutes(self):
    ...
@font_substitutes.setter
def font_substitutes(self, value):
    ...
```

### Lihat Juga
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
