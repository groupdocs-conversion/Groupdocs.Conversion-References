---
title: get_possible_conversions method
second_title: GroupDocs.Conversion for Python via .NET API References
description: "Retrieves possible conversions for the source document."
type: docs
url: /python-net/groupdocs.conversion.fluent/iconversionsourcedocumentloaded/get_possible_conversions/
is_root: false
weight: 1080
---


## get_possible_conversions

Retrieves possible conversions for the source document.

```python
def get_possible_conversions(self):
    ...
```

### Example

```python
from groupdocs.conversion import Converter

with Converter("report.xlsx") as converter:
    conversions = converter.get_possible_conversions()
    primary = [c.format for c in conversions.all if c.is_primary]
    print(f"Primary targets for {conversions.source.description}: {primary}")
```

### See Also
* class [`IConversionSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsourcedocumentloaded/)
