---
title: "méthode get_all_possible_conversions"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Obtient toutes les conversions prises en charge."
type: docs
url: /fr/python-net/groupdocs.conversion/converter/get_all_possible_conversions/
is_root: false
weight: 1070
---


## get_all_possible_conversions

Obtient toutes les conversions prises en charge.

En savoir plus sur les conversions prises en charge :
- [Full list of supported conversions](https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats)
- [How to get supported conversions in code](https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)

```python
def get_all_possible_conversions(cls):
    ...
```

**Returns:** Collection of all possible conversions.

### Exemple

```python
from groupdocs.conversion import Converter

# Récupérer toutes les conversions possibles
all_conversions = list(Converter.get_all_possible_conversions())
print(f"Total supported source formats: {len(all_conversions)}")
```

### Voir aussi
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
