---
title: "eigenschap on_conversion_failed"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "De gebeurtenisafhandelaar die wordt aangeroepen wanneer een conversie mislukt."
type: docs
url: /nl/python-net/groupdocs.conversion/convertersettings/on_conversion_failed/
is_root: false
weight: 2070
---


## on_conversion_failed property

De gebeurtenisafhandelaar die wordt aangeroepen wanneer een conversie mislukt.

Eerbetoon voor terugwaartse compatibiliteit: de waarde wordt samengevoegd in de interne events‑zak bij de constructie van [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) (in kaart gebracht naar [`ConversionEvents.on_document_failed`](/conversion/python-net/groupdocs.conversion/conversionevents/on_document_failed/)) en wordt overschreven als dezelfde handler ook is ingesteld op de `events` constructor‑parameter.

### Definition:
```python
@property
def on_conversion_failed(self):
    ...
@on_conversion_failed.setter
def on_conversion_failed(self, value):
    ...
```

### Zie ook
* class [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/)
