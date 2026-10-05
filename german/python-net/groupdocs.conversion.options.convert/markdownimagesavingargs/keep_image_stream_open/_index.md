---
title: "keep_image_stream_open-Eigenschaft"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Die Eigenschaft bestimmt, ob der Konverter den Bild-Stream nach der Konvertierung offen hält."
type: docs
url: /de/python-net/groupdocs.conversion.options.convert/markdownimagesavingargs/keep_image_stream_open/
is_root: false
weight: 2030
---


## keep_image_stream_open property

Die Eigenschaft bestimmt, ob der Konverter den Bild-Stream nach der Konvertierung offen hält.

Wenn False (Standard), schließt der Konverter [`MarkdownImageSavingArgs.image_stream`](/conversion/python-net/groupdocs.conversion.options.convert/markdownimagesavingargs/image_stream/) nach dem Schreiben – üblich für `io.RawIOBase`‑Ersetzungen, die auf die Festplatte geschrieben werden sollen. Auf True setzen, um den Stream nach Abschluss der Konvertierung offen zu halten (typisch für ein `io.BytesIO`, das Sie selbst lesen möchten); der Aufrufer ist dann für die Entsorgung verantwortlich.

### Definition:
```python
@property
def keep_image_stream_open(self):
    ...
@keep_image_stream_open.setter
def keep_image_stream_open(self, value):
    ...
```

### Siehe auch
* class [`MarkdownImageSavingArgs`](/conversion/python-net/groupdocs.conversion.options.convert/markdownimagesavingargs/)
