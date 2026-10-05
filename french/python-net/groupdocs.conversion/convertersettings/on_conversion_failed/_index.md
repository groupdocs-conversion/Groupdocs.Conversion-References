---
title: "propriété on_conversion_failed"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Le gestionnaire d'événement invoqué lorsqu'une conversion échoue."
type: docs
url: /fr/python-net/groupdocs.conversion/convertersettings/on_conversion_failed/
is_root: false
weight: 2070
---


## on_conversion_failed property

Le gestionnaire d'événement invoqué lorsqu'une conversion échoue.

Conservé pour la rétro‑compatibilité : la valeur est fusionnée dans le sac interne d'événements lors de la construction de [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) (mappée à [`ConversionEvents.on_document_failed`](/conversion/python-net/groupdocs.conversion/conversionevents/on_document_failed/)) et est remplacée si le même gestionnaire est également défini sur le paramètre du constructeur `events`.

### Definition:
```python
@property
def on_conversion_failed(self):
    ...
@on_conversion_failed.setter
def on_conversion_failed(self, value):
    ...
```

### Voir aussi
* class [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/)
