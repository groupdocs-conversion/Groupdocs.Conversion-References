---
title: "μέθοδος get_all_possible_conversions"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Λαμβάνει όλες τις υποστηριζόμενες μετατροπές."
type: docs
url: /el/python-net/groupdocs.conversion/converter/get_all_possible_conversions/
is_root: false
weight: 1070
---


## get_all_possible_conversions

Λαμβάνει όλες τις υποστηριζόμενες μετατροπές.

Μάθετε περισσότερα για τις υποστηριζόμενες μετατροπές:
- [Full list of supported conversions](https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats)
- [How to get supported conversions in code](https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)

```python
def get_all_possible_conversions(cls):
    ...
```

**Returns:** Collection of all possible conversions.

### Παράδειγμα

```python
from groupdocs.conversion import Converter

# Ανακτήστε όλες τις δυνατές μετατροπές
all_conversions = list(Converter.get_all_possible_conversions())
print(f"Total supported source formats: {len(all_conversions)}")
```

### Δείτε επίσης
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
