---
title: "свойство image_saving_callback"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Обратный вызов, вызываемый один раз для каждого изображения при сохранении Markdown."
type: docs
url: /ru/python-net/groupdocs.conversion.options.convert/markdownoptions/image_saving_callback/
is_root: false
weight: 2020
---


## image_saving_callback property

Обратный вызов, вызываемый один раз для каждого изображения при сохранении Markdown. Позволяет вызывающему сохранять изображения внешне и заменять URI, встроенный в документ. Имеет приоритет над [`MarkdownOptions.export_images_as_base64`](/conversion/python-net/groupdocs.conversion.options.convert/markdownoptions/export_images_as_base64/), если он не None.

### Definition:
```python
@property
def image_saving_callback(self):
    ...
@image_saving_callback.setter
def image_saving_callback(self, value):
    ...
```

### См. также
* class [`MarkdownOptions`](/conversion/python-net/groupdocs.conversion.options.convert/markdownoptions/)
