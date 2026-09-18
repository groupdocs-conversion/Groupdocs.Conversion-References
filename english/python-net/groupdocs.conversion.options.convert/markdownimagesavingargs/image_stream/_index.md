---
title: image_stream property
second_title: GroupDocs.Conversion for Python via .NET API References
description: "The destination stream the converter will write the image bytes into after this callback returns."
type: docs
url: /python-net/groupdocs.conversion.options.convert/markdownimagesavingargs/image_stream/
is_root: false
weight: 2020
---


## image_stream property

The destination stream the converter will write the image bytes into after this callback returns.

Replace it with your own writable stream (e.g., a `io.RawIOBase` for disk persistence or a `io.BytesIO` you intend to read afterwards).

### Definition:
```python
@property
def image_stream(self):
    ...
@image_stream.setter
def image_stream(self, value):
    ...
```

### See Also
* class [`MarkdownImageSavingArgs`](/conversion/python-net/groupdocs.conversion.options.convert/markdownimagesavingargs/)
