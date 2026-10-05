---
title: "schema_location Eigenschaft"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Der schemalocation ist eine durch Leerzeichen getrennte Liste von URI-Paaren, wobei die erste URI jedes Paares die Namespace-URI ist und die zweite URI den Pfad zum XML-Schema dieses Namespace angibt."
type: docs
url: /de/python-net/groupdocs.conversion.options.load/gmlloadoptions/schema_location/
is_root: false
weight: 2040
---


## schema_location property

Der schema_location ist eine durch Leerzeichen getrennte Liste von URI‑Paaren, wobei die erste URI jedes Paares die Namespace‑URI und die zweite URI der Pfad zum XML‑Schema dieses Namespace ist.

Wenn auf None gesetzt, versucht Conversion, das schemaLocation-Attribut aus dem Wurzelelement des Dokuments zu lesen. Der Standardwert ist None.

### Definition:
```python
@property
def schema_location(self):
    ...
@schema_location.setter
def schema_location(self, value):
    ...
```

### Siehe auch
* class [`GmlLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/gmlloadoptions/)
