---
title: "font_substitutes proprietà"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "I sostituti dei font utilizzati durante la conversione di un documento WordProcessing."
type: docs
url: /it/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_substitutes/
is_root: false
weight: 2140
---


## font_substitutes property

I sostituti dei font utilizzati durante la conversione di un documento WordProcessing.

Nota: L'ordine di sostituzione è il seguente:

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

### Vedi anche
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
