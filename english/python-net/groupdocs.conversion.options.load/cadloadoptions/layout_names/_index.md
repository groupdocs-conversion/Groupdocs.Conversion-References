---
title: layout_names property
second_title: GroupDocs.Conversion for Python via .NET API References
description: "The layout names to be converted."
type: docs
url: /python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/
is_root: false
weight: 2060
---


## layout_names property

The layout names to be converted.

Not honoured when converting to PDF/UA-1. That target renders the drawing as a single tagged page, which cannot carry one sheet per selected layout, so the whole drawing is converted instead and nothing here applies to it.

Every other target, PDF included, honours the selection. On those targets, names are matched exactly against the layouts the drawing carries, so a name that differs only in case is a different name. A name that matches nothing is dropped and costs the caller only that sheet; a list in which nothing matches fails the conversion with an `InvalidLoadOptionsException` naming the names that missed and the layouts the drawing does carry, rather than rendering sheets the caller did not ask for. A drawing that carries no layouts at all is exempt: there is nothing for a name to match, so none is refused.

### Definition:
```python
@property
def layout_names(self):
    ...
@layout_names.setter
def layout_names(self, value):
    ...
```

### See Also
* class [`CadLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/)
