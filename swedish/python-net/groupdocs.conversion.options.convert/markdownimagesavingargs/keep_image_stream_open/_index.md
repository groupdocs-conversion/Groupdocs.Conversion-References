---
title: "keep_image_stream_open egenskap"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Egenskapen bestämmer om konverteraren behåller bildströmmen öppen efter konvertering."
type: docs
url: /sv/python-net/groupdocs.conversion.options.convert/markdownimagesavingargs/keep_image_stream_open/
is_root: false
weight: 2030
---


## keep_image_stream_open property

Egenskapen bestämmer om konverteraren behåller bildströmmen öppen efter konvertering.

När False (standard) stänger konverteraren [`MarkdownImageSavingArgs.image_stream`](/conversion/python-net/groupdocs.conversion.options.convert/markdownimagesavingargs/image_stream/) efter skrivning — idiomatiskt för `io.RawIOBase`-ersättningar som bör spolas till disk. Sätt till True för att hålla strömmen öppen efter att konverteringen är klar (typiskt för en `io.BytesIO` som du avser att läsa själv); anroparen äger då ansvaret för borttagning.

### Definition:
```python
@property
def keep_image_stream_open(self):
    ...
@keep_image_stream_open.setter
def keep_image_stream_open(self, value):
    ...
```

### Se även
* class [`MarkdownImageSavingArgs`](/conversion/python-net/groupdocs.conversion.options.convert/markdownimagesavingargs/)
