---
title: schema_location property
second_title: GroupDocs.Conversion for Python via .NET API References
description: 
type: docs
weight: 80
url: /python-net/groupdocs.conversion.options.load/gmlloadoptions/schema_location/
is_root: false
---

## schema_location property


Space separated list of URI pairs. First URI in every pair is a URI of the namespace, second URI is a Path to XML schema of the namespace. If set to null, Conversion will try read schemaLocation from the root element of the document. Default is null
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
* module [`groupdocs.conversion.options.load`](../../)
* class [`GmlLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/gmlloadoptions)
