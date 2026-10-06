---
title: "image_saving_callback egenskap"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Callback-funktionen som anropas en gång per bild vid sparande av Markdown."
type: docs
url: /sv/python-net/groupdocs.conversion.options.convert/markdownoptions/image_saving_callback/
is_root: false
weight: 2020
---


## image_saving_callback property

Callback‑funktionen som anropas en gång per bild vid sparande av Markdown. Tillåter anroparen att lagra bilder externt och ersätta den URI som är inbäddad i dokumentet. Har företräde framför [`MarkdownOptions.export_images_as_base64`](/conversion/python-net/groupdocs.conversion.options.convert/markdownoptions/export_images_as_base64/) när den inte är None.

### Definition:
```python
@property
def image_saving_callback(self):
    ...
@image_saving_callback.setter
def image_saving_callback(self, value):
    ...
```

### Se även
* class [`MarkdownOptions`](/conversion/python-net/groupdocs.conversion.options.convert/markdownoptions/)
