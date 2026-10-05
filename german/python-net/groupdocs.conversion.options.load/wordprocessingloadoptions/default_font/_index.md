---
title: "default_font Eigenschaft"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Die Standardschriftart für ein WordProcessing‑Dokument."
type: docs
url: /de/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/default_font/
is_root: false
weight: 2080
---


## default_font property

Die Standardschriftart für ein WordProcessing‑Dokument.

Hinweis: Die Reihenfolge der Substitution ist wie folgt:
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

### Siehe auch
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
