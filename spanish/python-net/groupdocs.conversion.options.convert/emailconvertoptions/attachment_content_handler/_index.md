---
title: "attachment_content_handler propiedad"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "El delegado usado para manejar el procesamiento personalizado de los archivos adjuntos de correo electrónico."
type: docs
url: /es/python-net/groupdocs.conversion.options.convert/emailconvertoptions/attachment_content_handler/
is_root: false
weight: 2010
---


## attachment_content_handler property

El delegado usado para manejar el procesamiento personalizado de los archivos adjuntos de correo electrónico.

El delegado recibe el nombre del adjunto (`str`), el tipo de contenido (`str`) y el flujo original del adjunto (`io.RawIOBase`), y debe devolver un flujo de adjunto modificado (`io.RawIOBase`).

### Definition:
```python
@property
def attachment_content_handler(self):
    ...
@attachment_content_handler.setter
def attachment_content_handler(self, value):
    ...
```

### Ver también
* class [`EmailConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/emailconvertoptions/)
