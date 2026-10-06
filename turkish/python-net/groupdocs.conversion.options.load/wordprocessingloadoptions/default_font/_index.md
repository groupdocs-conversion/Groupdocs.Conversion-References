---
title: "default_font özelliği"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "WordProcessing belgesi için varsayılan yazı tipi."
type: docs
url: /tr/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/default_font/
is_root: false
weight: 2080
---


## default_font property

WordProcessing belgesi için varsayılan yazı tipi.

Not: Değiştirme sırası aşağıdaki gibidir:
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

### Ayrıca Bakınız
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
