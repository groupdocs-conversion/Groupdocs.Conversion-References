---
title: "eigenschap on_conversion_by_page_failed"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "De gebeurtenisafhandelaar die wordt aangeroepen wanneer conversie per pagina mislukt."
type: docs
url: /nl/python-net/groupdocs.conversion/convertersettings/on_conversion_by_page_failed/
is_root: false
weight: 2060
---


## on_conversion_by_page_failed property

De gebeurtenisafhandelaar die wordt aangeroepen wanneer conversie per pagina mislukt.

Gericht op terugwaartse compatibiliteit: de waarde wordt samengevoegd in de interne events‑bag bij de constructie van [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) (gemapt naar [`ConversionEvents.on_page_failed`](/conversion/python-net/groupdocs.conversion/conversionevents/on_page_failed/)) en wordt overschreven als dezelfde handler ook is ingesteld op de `events`-constructorparameter.

### Definition:
```python
@property
def on_conversion_by_page_failed(self):
    ...
@on_conversion_by_page_failed.setter
def on_conversion_by_page_failed(self, value):
    ...
```

### Zie ook
* class [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/)
