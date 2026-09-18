---
title: get_all_possible_conversions method
second_title: GroupDocs.Conversion for Python via .NET API References
description: "Gets all supported conversions."
type: docs
url: /python-net/groupdocs.conversion/converter/get_all_possible_conversions/
is_root: false
weight: 1070
---


## get_all_possible_conversions

Gets all supported conversions.

Learn more about supported conversions:
- [Full list of supported conversions](https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats)
- [How to get supported conversions in code](https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)

```python
def get_all_possible_conversions(cls):
    ...
```

**Returns:** Collection of all possible conversions.

### Example

```python
from groupdocs.conversion import Converter

# Retrieve all possible conversions
all_conversions = list(Converter.get_all_possible_conversions())
print(f"Total supported source formats: {len(all_conversions)}")
```

### See Also
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
