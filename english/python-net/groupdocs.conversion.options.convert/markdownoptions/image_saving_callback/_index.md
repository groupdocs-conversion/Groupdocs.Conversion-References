---
title: image_saving_callback property
second_title: GroupDocs.Conversion for Python via .NET API References
description: "The callback invoked once per image while saving Markdown."
type: docs
url: /python-net/groupdocs.conversion.options.convert/markdownoptions/image_saving_callback/
is_root: false
weight: 2020
---


## image_saving_callback property

The callback invoked once per image while saving Markdown. Allows the caller to persist images externally and substitute the URI embedded in the document. Takes precedence over [`MarkdownOptions.export_images_as_base64`](/conversion/python-net/groupdocs.conversion.options.convert/markdownoptions/export_images_as_base64/) when not None.

### Definition:
```python
@property
def image_saving_callback(self):
    ...
@image_saving_callback.setter
def image_saving_callback(self, value):
    ...
```

### See Also
* class [`MarkdownOptions`](/conversion/python-net/groupdocs.conversion.options.convert/markdownoptions/)
