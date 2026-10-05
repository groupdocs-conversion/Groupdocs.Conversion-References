---
title: "μέθοδος get_possible_conversions"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Ανακτά τις πιθανές μετατροπές για το πηγαίο έγγραφο."
type: docs
url: /el/python-net/groupdocs.conversion/converter/get_possible_conversions/
is_root: false
weight: 1090
---


## get_possible_conversions

Ανακτά τις πιθανές μετατροπές για το πηγαίο έγγραφο.

- Learn more about supported conversions: [Full list of supported conversions](https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats)
- Learn more about available conversions: [How to get supported conversions in code](https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)

```python
def get_possible_conversions(self):
    ...
```

**Returns:** PossibleConversions

### Παράδειγμα

```python
from groupdocs.conversion import Converter

with Converter("report.xlsx") as converter:
    conversions = converter.get_possible_conversions()
    primary = [c.format for c in conversions.all if c.is_primary]
    print(f"Primary targets for {conversions.source.description}: {primary}")
```

### Δείτε επίσης
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
