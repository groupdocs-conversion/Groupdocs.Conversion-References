---
title: "methode get_all_possible_conversions"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Haalt alle ondersteunde conversies op."
type: docs
url: /nl/python-net/groupdocs.conversion/converter/get_all_possible_conversions/
is_root: false
weight: 1070
---


## get_all_possible_conversions

Haalt alle ondersteunde conversies op.

Meer informatie over ondersteunde conversies:
- [Full list of supported conversions](https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats)
- [How to get supported conversions in code](https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)

```python
def get_all_possible_conversions(cls):
    ...
```

**Returns:** Collection of all possible conversions.

### Voorbeeld

```python
from groupdocs.conversion import Converter

# Alle mogelijke conversies ophalen
all_conversions = list(Converter.get_all_possible_conversions())
print(f"Total supported source formats: {len(all_conversions)}")
```

### Zie ook
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
