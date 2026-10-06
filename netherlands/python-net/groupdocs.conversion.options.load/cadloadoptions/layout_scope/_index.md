---
title: "layout_scope eigenschap"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "De layout‑scope die bepaalt welke tekenruimtes worden geconverteerd."
type: docs
url: /nl/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_scope/
is_root: false
weight: 2070
---


## layout_scope property

De lay-outscope die bepaalt welke tekenruimtes worden geconverteerd. Standaard is [`CadLayoutScope.both`](/conversion/python-net/groupdocs.conversion.options.load/cadlayoutscope/), wat de conversie niet beperkt. Wordt genegeerd wanneer [`CadLoadOptions.layout_names`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/) is opgegeven, omdat expliciete lay-outnamen altijd winnen. Een `None`-waarde wordt behandeld als [`CadLayoutScope.both`](/conversion/python-net/groupdocs.conversion.options.load/cadlayoutscope/).

Als de scope geen van de door een tekening aangeboden bladen selecteert, mislukt de conversie met `InvalidLoadOptionsException`, die de scope en de beschikbare bladen benoemt in plaats van de uitgesloten ruimtes weer te geven. Een tekening die helemaal geen blad aanbiedt, blijft onaangetast en wordt nog steeds als één eenheid geconverteerd. Niet gerespecteerd bij het converteren naar PDF/UA-1, om de reden die wordt gegeven op [`CadLoadOptions.layout_names`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/).

### Definition:
```python
@property
def layout_scope(self):
    ...
@layout_scope.setter
def layout_scope(self, value):
    ...
```

### Zie ook
* class [`CadLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/)
