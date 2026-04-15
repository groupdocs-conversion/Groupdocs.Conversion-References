---
title: schema_location property
second_title: GroupDocs.Conversion for Python via .NET API References
description: 
type: docs
url: /conversion/python-net/groupdocs.conversion.options.load/gmlloadoptions/schema_location/
is_root: false
weight: 2040
---


## schema_location property

The space-separated list of URI pairs, where the first URI in each pair is the namespace URI and the second URI is the path to the XML schema for that namespace.

If set to None, the conversion process will attempt to read the schemaLocation attribute from the root element of the document. The default value is None.

### Definition:
```python
@property
def schema_location(self):
    ...
@schema_location.setter
def schema_location(self, value):
    ...
```

### See Also
* class [`GmlLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/gmlloadoptions/)
