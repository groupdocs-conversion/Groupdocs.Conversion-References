---
title: "proprietà image_saving_callback"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Il callback invocato una volta per immagine durante il salvataggio di Markdown."
type: docs
url: /it/python-net/groupdocs.conversion.options.convert/markdownoptions/image_saving_callback/
is_root: false
weight: 2020
---


## image_saving_callback property

Il callback invocato una volta per immagine durante il salvataggio di Markdown. Consente al chiamante di persistere le immagini esternamente e sostituire l'URI incorporato nel documento. Ha la precedenza su [`MarkdownOptions.export_images_as_base64`](/conversion/python-net/groupdocs.conversion.options.convert/markdownoptions/export_images_as_base64/) quando non è None.

### Definition:
```python
@property
def image_saving_callback(self):
    ...
@image_saving_callback.setter
def image_saving_callback(self, value):
    ...
```

### Vedi anche
* class [`MarkdownOptions`](/conversion/python-net/groupdocs.conversion.options.convert/markdownoptions/)
