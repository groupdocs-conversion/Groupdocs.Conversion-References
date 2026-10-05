---
title: "propriété listener"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "L'implémentation du listener du convertisseur utilisée pour surveiller l'état et la progression de la conversion, avec ses rappels Started, Progress et Completed transmis à ConversionEvents.onconversionstarted…"
type: docs
url: /fr/python-net/groupdocs.conversion/convertersettings/listener/
is_root: false
weight: 2030
---


## listener property

L'implémentation du listener du convertisseur utilisée pour surveiller l'état et la progression de la conversion, avec ses callbacks Started, Progress et Completed transmis à [`ConversionEvents.on_conversion_started`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_started/), [`ConversionEvents.on_conversion_progress`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_progress/), et [`ConversionEvents.on_conversion_completed`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_completed/) pendant la construction de [`Converter`](/conversion/python-net/groupdocs.conversion/converter/).

### Definition:
```python
@property
def listener(self):
    ...
@listener.setter
def listener(self, value):
    ...
```

### Voir aussi
* class [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/)
