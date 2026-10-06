---
title: "proprietà keep_image_stream_open"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "La proprietà determina se il convertitore mantiene aperto il flusso dell'immagine dopo la conversione."
type: docs
url: /it/python-net/groupdocs.conversion.options.convert/markdownimagesavingargs/keep_image_stream_open/
is_root: false
weight: 2030
---


## keep_image_stream_open property

La proprietà determina se il convertitore mantiene aperto il flusso dell'immagine dopo la conversione.

Quando False (predefinito), il convertitore chiude [`MarkdownImageSavingArgs.image_stream`](/conversion/python-net/groupdocs.conversion.options.convert/markdownimagesavingargs/image_stream/) dopo la scrittura — comportamento tipico per le sostituzioni `io.RawIOBase` che devono essere svuotate su disco. Impostare a True per mantenere lo stream aperto dopo il completamento della conversione (tipico per un `io.BytesIO` che si intende leggere autonomamente); il chiamante gestisce quindi lo smaltimento.

### Definition:
```python
@property
def keep_image_stream_open(self):
    ...
@keep_image_stream_open.setter
def keep_image_stream_open(self, value):
    ...
```

### Vedi anche
* class [`MarkdownImageSavingArgs`](/conversion/python-net/groupdocs.conversion.options.convert/markdownimagesavingargs/)
