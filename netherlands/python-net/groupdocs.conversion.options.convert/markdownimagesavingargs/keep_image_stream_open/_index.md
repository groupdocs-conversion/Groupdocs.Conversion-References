---
title: "keep_image_stream_open eigenschap"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "De eigenschap bepaalt of de converter de afbeeldingsstroom open houdt na conversie."
type: docs
url: /nl/python-net/groupdocs.conversion.options.convert/markdownimagesavingargs/keep_image_stream_open/
is_root: false
weight: 2030
---


## keep_image_stream_open property

De eigenschap bepaalt of de converter de afbeeldingsstroom open houdt na conversie.

Wanneer False (standaard) sluit de converter [`MarkdownImageSavingArgs.image_stream`](/conversion/python-net/groupdocs.conversion.options.convert/markdownimagesavingargs/image_stream/) na het schrijven — gebruikelijk voor `io.RawIOBase`‑vervangingen die naar schijf moeten worden weggeschreven. Stel in op True om de stream open te houden nadat de conversie is voltooid (typisch voor een `io.BytesIO` die je zelf wilt lezen); de aanroeper bezit daarna de verwijdering.

### Definition:
```python
@property
def keep_image_stream_open(self):
    ...
@keep_image_stream_open.setter
def keep_image_stream_open(self, value):
    ...
```

### Zie ook
* class [`MarkdownImageSavingArgs`](/conversion/python-net/groupdocs.conversion.options.convert/markdownimagesavingargs/)
