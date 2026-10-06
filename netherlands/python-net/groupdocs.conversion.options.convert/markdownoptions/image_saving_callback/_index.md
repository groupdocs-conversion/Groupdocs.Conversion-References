---
title: "image_saving_callback eigenschap"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "De callback die één keer per afbeelding wordt aangeroepen tijdens het opslaan van Markdown."
type: docs
url: /nl/python-net/groupdocs.conversion.options.convert/markdownoptions/image_saving_callback/
is_root: false
weight: 2020
---


## image_saving_callback property

De callback die eenmaal per afbeelding wordt aangeroepen tijdens het opslaan van Markdown. Hiermee kan de aanroeper afbeeldingen extern opslaan en de in het document ingebedde URI vervangen. Heeft voorrang op [`MarkdownOptions.export_images_as_base64`](/conversion/python-net/groupdocs.conversion.options.convert/markdownoptions/export_images_as_base64/) wanneer deze niet None is.

### Definition:
```python
@property
def image_saving_callback(self):
    ...
@image_saving_callback.setter
def image_saving_callback(self, value):
    ...
```

### Zie ook
* class [`MarkdownOptions`](/conversion/python-net/groupdocs.conversion.options.convert/markdownoptions/)
