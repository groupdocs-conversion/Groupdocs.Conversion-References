---
title: "Methode get_all_possible_conversions"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Ermittelt alle unterstützten Konvertierungen."
type: docs
url: /de/python-net/groupdocs.conversion/converter/get_all_possible_conversions/
is_root: false
weight: 1070
---


## get_all_possible_conversions

Ermittelt alle unterstützten Konvertierungen.

Erfahren Sie mehr über unterstützte Konvertierungen:
- [Full list of supported conversions](https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats)
- [How to get supported conversions in code](https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)

```python
def get_all_possible_conversions(cls):
    ...
```

**Returns:** Collection of all possible conversions.

### Beispiel

```python
from groupdocs.conversion import Converter

# Alle möglichen Konvertierungen abrufen
all_conversions = list(Converter.get_all_possible_conversions())
print(f"Total supported source formats: {len(all_conversions)}")
```

### Siehe auch
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
