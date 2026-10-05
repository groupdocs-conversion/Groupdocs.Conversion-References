---
title: "Méthode get_possible_conversions"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Récupère les conversions possibles pour le document source."
type: docs
url: /fr/python-net/groupdocs.conversion.fluent/iconversionsourcedocumentloaded/get_possible_conversions/
is_root: false
weight: 1080
---


## get_possible_conversions

Récupère les conversions possibles pour le document source.

```python
def get_possible_conversions(self):
    ...
```

### Exemple

```python
from groupdocs.conversion import Converter

with Converter("report.xlsx") as converter:
    conversions = converter.get_possible_conversions()
    primary = [c.format for c in conversions.all if c.is_primary]
    print(f"Primary targets for {conversions.source.description}: {primary}")
```

### Voir aussi
* class [`IConversionSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsourcedocumentloaded/)
