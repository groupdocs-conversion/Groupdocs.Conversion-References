---
title: restore_schema property
second_title: GroupDocs.Conversion for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.conversion.options.load/gmlloadoptions/restore_schema/
is_root: false
weight: 2030
---


## restore_schema property

The property determines whether conversion is allowed to parse attributes in a GML file when the XML schema is missing or cannot be loaded.

If set to True, the conversion reader does not require the presence of an XML schema. The default value is False.

### Definition:
```python
@property
def restore_schema(self):
    ...
@restore_schema.setter
def restore_schema(self, value):
    ...
```

### See Also
* class [`GmlLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/gmlloadoptions/)
