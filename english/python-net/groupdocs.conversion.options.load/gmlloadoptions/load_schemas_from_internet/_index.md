---
title: load_schemas_from_internet property
second_title: GroupDocs.Conversion for Python via .NET API References
description: 
type: docs
url: /conversion/python-net/groupdocs.conversion.options.load/gmlloadoptions/load_schemas_from_internet/
is_root: false
weight: 2020
---


## load_schemas_from_internet property

The property determines whether conversion is allowed to load XML schema from the Internet.

If set to False, schemas with absolute URIs that do not start with 'file://' will not be loaded. Default is False.

### Definition:
```python
@property
def load_schemas_from_internet(self):
    ...
@load_schemas_from_internet.setter
def load_schemas_from_internet(self, value):
    ...
```

### See Also
* class [`GmlLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/gmlloadoptions/)
