---
title: "get_possible_conversions methode"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Haalt mogelijke conversies op voor het bron document."
type: docs
url: /nl/python-net/groupdocs.conversion/converter/get_possible_conversions/
is_root: false
weight: 1090
---


## get_possible_conversions

Haalt mogelijke conversies op voor het bron document.

- Learn more about supported conversions: [Full list of supported conversions](https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats)
- Learn more about available conversions: [How to get supported conversions in code](https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)

```python
def get_possible_conversions(self):
    ...
```

**Returns:** PossibleConversions

### Voorbeeld

```python
from groupdocs.conversion import Converter

with Converter("report.xlsx") as converter:
    conversions = converter.get_possible_conversions()
    primary = [c.format for c in conversions.all if c.is_primary]
    print(f"Primary targets for {conversions.source.description}: {primary}")
```

### Zie ook
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
