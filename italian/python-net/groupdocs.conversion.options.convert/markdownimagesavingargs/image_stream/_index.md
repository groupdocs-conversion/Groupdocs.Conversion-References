---
title: "proprietà image_stream"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Il flusso di destinazione in cui il convertitore scriverà i byte dell'immagine dopo che questa callback restituisce."
type: docs
url: /it/python-net/groupdocs.conversion.options.convert/markdownimagesavingargs/image_stream/
is_root: false
weight: 2020
---


## image_stream property

Il flusso di destinazione in cui il convertitore scriverà i byte dell'immagine dopo che questa callback restituisce.

Sostituirlo con il proprio stream scrivibile (ad esempio, un `io.RawIOBase` per la persistenza su disco o un `io.BytesIO` che si intende leggere successivamente).

### Definition:
```python
@property
def image_stream(self):
    ...
@image_stream.setter
def image_stream(self, value):
    ...
```

### Vedi anche
* class [`MarkdownImageSavingArgs`](/conversion/python-net/groupdocs.conversion.options.convert/markdownimagesavingargs/)
