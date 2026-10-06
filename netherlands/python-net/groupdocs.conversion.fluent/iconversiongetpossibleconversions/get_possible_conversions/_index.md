---
title: "get_possible_conversions methode"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Haalt mogelijke conversies op voor het bron document."
type: docs
url: /nl/python-net/groupdocs.conversion.fluent/iconversiongetpossibleconversions/get_possible_conversions/
is_root: false
weight: 1010
---


## get_possible_conversions

Haalt mogelijke conversies op voor het bron document.

```python
def get_possible_conversions(self):
    ...
```

**Returns:** A `GroupDocs.Conversion.Fluent.PossibleConversions` object containing the source description and a collection of conversion options.

### Voorbeeld

```python
from groupdocs.conversion import Converter

with Converter("report.xlsx") as converter:
    conversions = converter.get_possible_conversions()
    primary = [c.format for c in conversions.all if c.is_primary]
    print(f"Primary targets for {conversions.source.description}: {primary}")
```

### Zie ook
* class [`IConversionGetPossibleConversions`](/conversion/python-net/groupdocs.conversion.fluent/iconversiongetpossibleconversions/)
