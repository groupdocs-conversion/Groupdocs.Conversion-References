---
title: "propriété on_conversion_by_page_failed"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Le gestionnaire d'événement invoqué lorsque la conversion par page échoue."
type: docs
url: /fr/python-net/groupdocs.conversion/convertersettings/on_conversion_by_page_failed/
is_root: false
weight: 2060
---


## on_conversion_by_page_failed property

Le gestionnaire d'événement invoqué lorsque la conversion par page échoue.

Respecté pour la rétro‑compatibilité : la valeur est fusionnée dans le sac d'événements interne lors de la construction de [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) (mappage vers [`ConversionEvents.on_page_failed`](/conversion/python-net/groupdocs.conversion/conversionevents/on_page_failed/)) et est remplacée si le même gestionnaire est également défini sur le paramètre du constructeur `events`.

### Definition:
```python
@property
def on_conversion_by_page_failed(self):
    ...
@on_conversion_by_page_failed.setter
def on_conversion_by_page_failed(self, value):
    ...
```

### Voir aussi
* class [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/)
