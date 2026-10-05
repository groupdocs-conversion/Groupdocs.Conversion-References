---
title: "propriété keep_image_stream_open"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "La propriété détermine si le convertisseur maintient le flux d'image ouvert après la conversion."
type: docs
url: /fr/python-net/groupdocs.conversion.options.convert/markdownimagesavingargs/keep_image_stream_open/
is_root: false
weight: 2030
---


## keep_image_stream_open property

La propriété détermine si le convertisseur maintient le flux d'image ouvert après la conversion.

Lorsque False (par défaut), le convertisseur ferme [`MarkdownImageSavingArgs.image_stream`](/conversion/python-net/groupdocs.conversion.options.convert/markdownimagesavingargs/image_stream/) après l’écriture — ce qui est idiomatique pour les remplacements `io.RawIOBase` qui doivent être vidés sur le disque. Définissez à True pour garder le flux ouvert après la fin de la conversion (typique pour un `io.BytesIO` que vous prévoyez de lire vous‑même) ; l’appelant en possède alors la disposition.

### Definition:
```python
@property
def keep_image_stream_open(self):
    ...
@keep_image_stream_open.setter
def keep_image_stream_open(self, value):
    ...
```

### Voir aussi
* class [`MarkdownImageSavingArgs`](/conversion/python-net/groupdocs.conversion.options.convert/markdownimagesavingargs/)
