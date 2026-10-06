---
title: "attachment_content_handler egenskap"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Delegaten som används för att hantera anpassad bearbetning av e-postbilagor."
type: docs
url: /sv/python-net/groupdocs.conversion.options.convert/emailconvertoptions/attachment_content_handler/
is_root: false
weight: 2010
---


## attachment_content_handler property

Delegaten som används för att hantera anpassad bearbetning av e-postbilagor.

Delegaten tar emot bilaganamnet (`str`), innehållstypen (`str`) och den ursprungliga bilagaströmmen (`io.RawIOBase`) och måste returnera en modifierad bilagaström (`io.RawIOBase`).

### Definition:
```python
@property
def attachment_content_handler(self):
    ...
@attachment_content_handler.setter
def attachment_content_handler(self, value):
    ...
```

### Se även
* class [`EmailConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/emailconvertoptions/)
