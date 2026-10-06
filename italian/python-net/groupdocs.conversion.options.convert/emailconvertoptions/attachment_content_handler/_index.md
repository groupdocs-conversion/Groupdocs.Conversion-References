---
title: "attachment_content_handler proprietà"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Il delegato utilizzato per gestire l'elaborazione personalizzata degli allegati email."
type: docs
url: /it/python-net/groupdocs.conversion.options.convert/emailconvertoptions/attachment_content_handler/
is_root: false
weight: 2010
---


## attachment_content_handler property

Il delegato utilizzato per gestire l'elaborazione personalizzata degli allegati email.

Il delegato riceve il nome dell'allegato (`str`), il tipo di contenuto (`str`) e lo stream originale dell'allegato (`io.RawIOBase`), e deve restituire uno stream dell'allegato modificato (`io.RawIOBase`).

### Definition:
```python
@property
def attachment_content_handler(self):
    ...
@attachment_content_handler.setter
def attachment_content_handler(self, value):
    ...
```

### Vedi anche
* class [`EmailConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/emailconvertoptions/)
