---
title: attachment_content_handler property
second_title: GroupDocs.Conversion for Python via .NET API References
description: "The delegate used to handle custom processing of email attachments."
type: docs
url: /python-net/groupdocs.conversion.options.convert/emailconvertoptions/attachment_content_handler/
is_root: false
weight: 2010
---


## attachment_content_handler property

The delegate used to handle custom processing of email attachments.

The delegate receives the attachment name (`str`), content type (`str`), and the original attachment stream (`io.RawIOBase`), and must return a modified attachment stream (`io.RawIOBase`).

### Definition:
```python
@property
def attachment_content_handler(self):
    ...
@attachment_content_handler.setter
def attachment_content_handler(self, value):
    ...
```

### See Also
* class [`EmailConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/emailconvertoptions/)
