---
title: "Método get_all_possible_conversions"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Obtiene todas las conversiones compatibles."
type: docs
url: /es/python-net/groupdocs.conversion/converter/get_all_possible_conversions/
is_root: false
weight: 1070
---


## get_all_possible_conversions

Obtiene todas las conversiones compatibles.

Obtén más información sobre las conversiones compatibles:
- [Full list of supported conversions](https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats)
- [How to get supported conversions in code](https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)

```python
def get_all_possible_conversions(cls):
    ...
```

**Returns:** Collection of all possible conversions.

### Ejemplo

```python
from groupdocs.conversion import Converter

# Obtener todas las conversiones posibles
all_conversions = list(Converter.get_all_possible_conversions())
print(f"Total supported source formats: {len(all_conversions)}")
```

### Ver también
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
