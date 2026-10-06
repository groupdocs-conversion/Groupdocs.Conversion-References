---
title: "Metodo get_possible_conversions"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Recupera le conversioni possibili per il documento di origine."
type: docs
url: /it/python-net/groupdocs.conversion.fluent/iconversionsourcedocumentloaded/get_possible_conversions/
is_root: false
weight: 1080
---


## get_possible_conversions

Recupera le conversioni possibili per il documento di origine.

```python
def get_possible_conversions(self):
    ...
```

### Esempio

```python
from groupdocs.conversion import Converter

with Converter("report.xlsx") as converter:
    conversions = converter.get_possible_conversions()
    primary = [c.format for c in conversions.all if c.is_primary]
    print(f"Primary targets for {conversions.source.description}: {primary}")
```

### Vedi anche
* class [`IConversionSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsourcedocumentloaded/)
