---
title: "propriété attachment_content_handler"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Le délégué utilisé pour gérer le traitement personnalisé des pièces jointes d'e‑mail."
type: docs
url: /fr/python-net/groupdocs.conversion.options.convert/emailconvertoptions/attachment_content_handler/
is_root: false
weight: 2010
---


## attachment_content_handler property

Le délégué utilisé pour gérer le traitement personnalisé des pièces jointes d'e‑mail.

Le délégué reçoit le nom de la pièce jointe (`str`), le type de contenu (`str`) et le flux de la pièce jointe original (`io.RawIOBase`), et doit renvoyer un flux de pièce jointe modifié (`io.RawIOBase`).

### Definition:
```python
@property
def attachment_content_handler(self):
    ...
@attachment_content_handler.setter
def attachment_content_handler(self, value):
    ...
```

### Voir aussi
* class [`EmailConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/emailconvertoptions/)
