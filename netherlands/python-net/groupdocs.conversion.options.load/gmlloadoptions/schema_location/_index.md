---
title: "schema_location eigenschap"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "De schemalocatie is een door spaties gescheiden lijst van URI‑paren, waarbij de eerste URI in elk paar de namespace‑URI is en de tweede URI het pad naar het XML‑schema van die namespace."
type: docs
url: /nl/python-net/groupdocs.conversion.options.load/gmlloadoptions/schema_location/
is_root: false
weight: 2040
---


## schema_location property

De schema_location is een door spaties gescheiden lijst van URI-paren, waarbij de eerste URI in elk paar de namespace-URI is en de tweede URI het pad naar het XML-schema van die namespace.

Indien ingesteld op None, zal Conversion proberen het schemaLocation‑attribuut uit het root‑element van het document te lezen. De standaardwaarde is None.

### Definition:
```python
@property
def schema_location(self):
    ...
@schema_location.setter
def schema_location(self, value):
    ...
```

### Zie ook
* class [`GmlLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/gmlloadoptions/)
