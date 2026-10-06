---
title: "metoden get_all_possible_conversions"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Hämtar alla stödda konverteringar."
type: docs
url: /sv/python-net/groupdocs.conversion/converter/get_all_possible_conversions/
is_root: false
weight: 1070
---


## get_all_possible_conversions

Hämtar alla stödda konverteringar.

Läs mer om stödjade konverteringar:
- [Full list of supported conversions](https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats)
- [How to get supported conversions in code](https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)

```python
def get_all_possible_conversions(cls):
    ...
```

**Returns:** Collection of all possible conversions.

### Exempel

```python
from groupdocs.conversion import Converter

# Hämta alla möjliga konverteringar
all_conversions = list(Converter.get_all_possible_conversions())
print(f"Total supported source formats: {len(all_conversions)}")
```

### Se även
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
