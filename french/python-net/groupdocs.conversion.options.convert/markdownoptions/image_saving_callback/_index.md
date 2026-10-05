---
title: "image_saving_callback propriété"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Le rappel invoqué une fois par image lors de l'enregistrement du Markdown."
type: docs
url: /fr/python-net/groupdocs.conversion.options.convert/markdownoptions/image_saving_callback/
is_root: false
weight: 2020
---


## image_saving_callback property

Le rappel invoqué une fois par image lors de l'enregistrement du Markdown. Permet à l'appelant de persister les images à l'extérieur et de substituer l'URI intégré dans le document. Prend le pas sur [`MarkdownOptions.export_images_as_base64`](/conversion/python-net/groupdocs.conversion.options.convert/markdownoptions/export_images_as_base64/) lorsqu'il n'est pas None.

### Definition:
```python
@property
def image_saving_callback(self):
    ...
@image_saving_callback.setter
def image_saving_callback(self, value):
    ...
```

### Voir aussi
* class [`MarkdownOptions`](/conversion/python-net/groupdocs.conversion.options.convert/markdownoptions/)
