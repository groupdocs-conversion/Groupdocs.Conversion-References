---
title: "propiedad keep_image_stream_open"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "La propiedad determina si el convertidor mantiene abierto el flujo de imagen después de la conversión."
type: docs
url: /es/python-net/groupdocs.conversion.options.convert/markdownimagesavingargs/keep_image_stream_open/
is_root: false
weight: 2030
---


## keep_image_stream_open property

La propiedad determina si el convertidor mantiene abierto el flujo de imagen después de la conversión.

Cuando es False (por defecto), el convertidor cierra [`MarkdownImageSavingArgs.image_stream`](/conversion/python-net/groupdocs.conversion.options.convert/markdownimagesavingargs/image_stream/) después de escribir — de forma idiomática para reemplazos `io.RawIOBase` que deben vaciarse en disco. Establézcalo en True para mantener el flujo abierto después de que la conversión finalice (típico para un `io.BytesIO` que pretenda leer usted mismo); el llamador entonces es responsable de su eliminación.

### Definition:
```python
@property
def keep_image_stream_open(self):
    ...
@keep_image_stream_open.setter
def keep_image_stream_open(self, value):
    ...
```

### Ver también
* class [`MarkdownImageSavingArgs`](/conversion/python-net/groupdocs.conversion.options.convert/markdownimagesavingargs/)
