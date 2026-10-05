---
title: "image_saving_callback properti"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Callback yang dipanggil sekali per gambar saat menyimpan Markdown."
type: docs
url: /id/python-net/groupdocs.conversion.options.convert/markdownoptions/image_saving_callback/
is_root: false
weight: 2020
---


## image_saving_callback property

Callback yang dipanggil sekali per gambar saat menyimpan Markdown. Memungkinkan pemanggil untuk menyimpan gambar secara eksternal dan mengganti URI yang disematkan dalam dokumen. Memiliki prioritas lebih tinggi daripada [`MarkdownOptions.export_images_as_base64`](/conversion/python-net/groupdocs.conversion.options.convert/markdownoptions/export_images_as_base64/) ketika tidak None.

### Definition:
```python
@property
def image_saving_callback(self):
    ...
@image_saving_callback.setter
def image_saving_callback(self, value):
    ...
```

### Lihat Juga
* class [`MarkdownOptions`](/conversion/python-net/groupdocs.conversion.options.convert/markdownoptions/)
