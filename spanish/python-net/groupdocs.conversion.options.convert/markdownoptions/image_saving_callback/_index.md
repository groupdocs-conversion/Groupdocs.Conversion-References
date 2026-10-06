---
title: "image_saving_callback propiedad"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "La devolución de llamada invocada una vez por imagen al guardar Markdown."
type: docs
url: /es/python-net/groupdocs.conversion.options.convert/markdownoptions/image_saving_callback/
is_root: false
weight: 2020
---


## image_saving_callback property

La devolución de llamada invocada una vez por imagen al guardar Markdown. Permite al llamador persistir imágenes externamente y sustituir el URI incrustado en el documento. Tiene precedencia sobre [`MarkdownOptions.export_images_as_base64`](/conversion/python-net/groupdocs.conversion.options.convert/markdownoptions/export_images_as_base64/) cuando no es None.

### Definition:
```python
@property
def image_saving_callback(self):
    ...
@image_saving_callback.setter
def image_saving_callback(self, value):
    ...
```

### Ver también
* class [`MarkdownOptions`](/conversion/python-net/groupdocs.conversion.options.convert/markdownoptions/)
