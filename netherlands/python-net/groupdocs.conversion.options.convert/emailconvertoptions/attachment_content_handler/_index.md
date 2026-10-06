---
title: "attachment_content_handler eigenschap"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "De delegate die wordt gebruikt om aangepaste verwerking van e-mailbijlagen af te handelen."
type: docs
url: /nl/python-net/groupdocs.conversion.options.convert/emailconvertoptions/attachment_content_handler/
is_root: false
weight: 2010
---


## attachment_content_handler property

De delegate die wordt gebruikt om aangepaste verwerking van e-mailbijlagen af te handelen.

De delegate ontvangt de bijlage‑naam (`str`), content‑type (`str`) en de originele bijlage‑stream (`io.RawIOBase`), en moet een gewijzigde bijlage‑stream (`io.RawIOBase`) retourneren.

### Definition:
```python
@property
def attachment_content_handler(self):
    ...
@attachment_content_handler.setter
def attachment_content_handler(self, value):
    ...
```

### Zie ook
* class [`EmailConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/emailconvertoptions/)
