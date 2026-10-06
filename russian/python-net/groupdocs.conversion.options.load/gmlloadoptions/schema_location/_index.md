---
title: "свойство schema_location"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "schemalocation — это список пар URI, разделённых пробелами, где первый URI в каждой паре является URI пространства имён, а второй URI — путь к XML‑схеме этого пространства имён."
type: docs
url: /ru/python-net/groupdocs.conversion.options.load/gmlloadoptions/schema_location/
is_root: false
weight: 2040
---


## schema_location property

Параметр schema_location представляет собой список пар URI, разделённых пробелами, где первый URI в каждой паре — URI пространства имён, а второй URI — путь к XML‑схеме этого пространства имён.

Если установить в None, Conversion попытается прочитать атрибут schemaLocation из корневого элемента документа. Значение по умолчанию — None.

### Definition:
```python
@property
def schema_location(self):
    ...
@schema_location.setter
def schema_location(self, value):
    ...
```

### См. также
* class [`GmlLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/gmlloadoptions/)
