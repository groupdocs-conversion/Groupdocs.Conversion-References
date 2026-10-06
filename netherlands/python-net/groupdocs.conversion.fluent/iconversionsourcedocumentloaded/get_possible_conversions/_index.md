---
title: "get_possible_conversions methode"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Haalt mogelijke conversies op voor het bron document."
type: docs
url: /nl/python-net/groupdocs.conversion.fluent/iconversionsourcedocumentloaded/get_possible_conversions/
is_root: false
weight: 1080
---


## get_possible_conversions

Haalt mogelijke conversies op voor het bron document.

```python
def get_possible_conversions(self):
    ...
```

### Voorbeeld

```python
from groupdocs.conversion import Converter

with Converter("report.xlsx") as converter:
    conversions = converter.get_possible_conversions()
    primary = [c.format for c in conversions.all if c.is_primary]
    print(f"Primary targets for {conversions.source.description}: {primary}")
```

### Zie ook
* class [`IConversionSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsourcedocumentloaded/)
