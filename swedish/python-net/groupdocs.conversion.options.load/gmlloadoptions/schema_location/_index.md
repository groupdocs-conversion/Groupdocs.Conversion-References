---
title: "schema_location‑egenskap"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Schemalocation är en blankstegsavgränsad lista med URI-par, där den första URI:n i varje par är namnrymdens URI och den andra URI:n är sökvägen till XML-schemat för den namnrymden."
type: docs
url: /sv/python-net/groupdocs.conversion.options.load/gmlloadoptions/schema_location/
is_root: false
weight: 2040
---


## schema_location property

schema_location är en mellanslagsseparerad lista med URI-par, där den första URI:n i varje par är namnrymdens URI och den andra URI:n är sökvägen till XML-schemat för den namnrymden.

Om den är satt till None kommer Conversion att försöka läsa schemaLocation‑attributet från dokumentets rotnod. Standardvärdet är None.

### Definition:
```python
@property
def schema_location(self):
    ...
@schema_location.setter
def schema_location(self, value):
    ...
```

### Se även
* class [`GmlLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/gmlloadoptions/)
