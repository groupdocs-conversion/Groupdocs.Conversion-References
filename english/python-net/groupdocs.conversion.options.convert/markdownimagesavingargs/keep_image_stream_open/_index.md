---
title: keep_image_stream_open property
second_title: GroupDocs.Conversion for Python via .NET API References
description: "The property determines whether the converter keeps the image stream open after conversion."
type: docs
url: /python-net/groupdocs.conversion.options.convert/markdownimagesavingargs/keep_image_stream_open/
is_root: false
weight: 2030
---


## keep_image_stream_open property

The property determines whether the converter keeps the image stream open after conversion.

When False (default), the converter closes [`MarkdownImageSavingArgs.image_stream`](/conversion/python-net/groupdocs.conversion.options.convert/markdownimagesavingargs/image_stream/) after writing — idiomatic for `io.RawIOBase` replacements that should be flushed to disk. Set to True to keep the stream open after conversion completes (typical for a `io.BytesIO` you intend to read yourself); the caller then owns disposal.

### Definition:
```python
@property
def keep_image_stream_open(self):
    ...
@keep_image_stream_open.setter
def keep_image_stream_open(self, value):
    ...
```

### See Also
* class [`MarkdownImageSavingArgs`](/conversion/python-net/groupdocs.conversion.options.convert/markdownimagesavingargs/)
