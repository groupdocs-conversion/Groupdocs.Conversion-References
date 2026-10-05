---
title: "get_possible_conversions Methode"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Ruft mögliche Konvertierungen für das Quell-Dokument ab."
type: docs
url: /de/python-net/groupdocs.conversion/converter/get_possible_conversions/
is_root: false
weight: 1090
---


## get_possible_conversions

Ruft mögliche Konvertierungen für das Quell-Dokument ab.

- Learn more about supported conversions: [Full list of supported conversions](https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats)
- Learn more about available conversions: [How to get supported conversions in code](https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)

```python
def get_possible_conversions(self):
    ...
```

**Returns:** PossibleConversions

### Beispiel

```python
from groupdocs.conversion import Converter

with Converter("report.xlsx") as converter:
    conversions = converter.get_possible_conversions()
    primary = [c.format for c in conversions.all if c.is_primary]
    print(f"Primary targets for {conversions.source.description}: {primary}")
```

### Siehe auch
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
