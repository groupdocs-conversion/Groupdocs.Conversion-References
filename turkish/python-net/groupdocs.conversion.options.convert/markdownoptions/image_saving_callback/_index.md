---
title: "image_saving_callback özelliği"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Markdown kaydedilirken her görüntü için bir kez çağrılan callback."
type: docs
url: /tr/python-net/groupdocs.conversion.options.convert/markdownoptions/image_saving_callback/
is_root: false
weight: 2020
---


## image_saving_callback property

Markdown kaydedilirken her görüntü için bir kez çağrılan geri arama. Çağırana görüntüleri harici olarak kalıcı tutma ve belgede gömülü URI'yi değiştirme imkanı verir. None olmadığında [`MarkdownOptions.export_images_as_base64`](/conversion/python-net/groupdocs.conversion.options.convert/markdownoptions/export_images_as_base64/) üzerine öncelik alır.

### Definition:
```python
@property
def image_saving_callback(self):
    ...
@image_saving_callback.setter
def image_saving_callback(self, value):
    ...
```

### Ayrıca Bakınız
* class [`MarkdownOptions`](/conversion/python-net/groupdocs.conversion.options.convert/markdownoptions/)
