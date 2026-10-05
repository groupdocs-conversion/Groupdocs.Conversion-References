---
title: "attachment_content_handler Eigenschaft"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Der Delegat, der zur Verarbeitung benutzerdefinierter E-Mail-Anhänge verwendet wird."
type: docs
url: /de/python-net/groupdocs.conversion.options.convert/emailconvertoptions/attachment_content_handler/
is_root: false
weight: 2010
---


## attachment_content_handler property

Der Delegat, der zur Verarbeitung benutzerdefinierter E-Mail-Anhänge verwendet wird.

Der Delegat erhält den Anhangsnamen (`str`), den Inhaltstyp (`str`) und den ursprünglichen Anhangsstrom (`io.RawIOBase`) und muss einen modifizierten Anhangsstrom (`io.RawIOBase`) zurückgeben.

### Definition:
```python
@property
def attachment_content_handler(self):
    ...
@attachment_content_handler.setter
def attachment_content_handler(self, value):
    ...
```

### Siehe auch
* class [`EmailConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/emailconvertoptions/)
