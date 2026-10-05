---
title: "image_saving_callback-Eigenschaft"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Der Callback, der beim Speichern von Markdown einmal pro Bild aufgerufen wird."
type: docs
url: /de/python-net/groupdocs.conversion.options.convert/markdownoptions/image_saving_callback/
is_root: false
weight: 2020
---


## image_saving_callback property

Der Callback, der beim Speichern von Markdown einmal pro Bild aufgerufen wird. Ermöglicht dem Aufrufer, Bilder extern zu speichern und die im Dokument eingebettete URI zu ersetzen. Hat Vorrang vor [`MarkdownOptions.export_images_as_base64`](/conversion/python-net/groupdocs.conversion.options.convert/markdownoptions/export_images_as_base64/), wenn nicht None.

### Definition:
```python
@property
def image_saving_callback(self):
    ...
@image_saving_callback.setter
def image_saving_callback(self, value):
    ...
```

### Siehe auch
* class [`MarkdownOptions`](/conversion/python-net/groupdocs.conversion.options.convert/markdownoptions/)
