---
title: "metodo get_all_possible_conversions"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Ottiene tutte le conversioni supportate."
type: docs
url: /it/python-net/groupdocs.conversion/converter/get_all_possible_conversions/
is_root: false
weight: 1070
---


## get_all_possible_conversions

Ottiene tutte le conversioni supportate.

Scopri di più sulle conversioni supportate:
- [Full list of supported conversions](https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats)
- [How to get supported conversions in code](https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)

```python
def get_all_possible_conversions(cls):
    ...
```

**Returns:** Collection of all possible conversions.

### Esempio

```python
from groupdocs.conversion import Converter

# Recupera tutte le conversioni possibili
all_conversions = list(Converter.get_all_possible_conversions())
print(f"Total supported source formats: {len(all_conversions)}")
```

### Vedi anche
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
