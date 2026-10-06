---
title: "get_possible_conversions methode"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Haalt mogelijke conversies op voor het bron document."
type: docs
url: /nl/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/get_possible_conversions/
is_root: false
weight: 1080
---


## get_possible_conversions

Haalt mogelijke conversies op voor het bron document.

Het geretourneerde object biedt toegang tot alle conversieopties, inclusief primaire en secundaire formaten, en bevat metadata over het bronbestand.

```python
def get_possible_conversions(self):
    ...
```

**Returns:** GroupDocs.Conversion.Fluent.PossibleConversions: An object containing the source description and collections of conversion formats.

### Voorbeeld

```python
from groupdocs.conversion import Converter

with Converter("report.xlsx") as converter:
    conversions = converter.get_possible_conversions()
    primary = [c.format for c in conversions.all if c.is_primary]
    print(f"Primary targets for {conversions.source.description}: {primary}")
```

### Zie ook
* class [`IConversionLoadOptionsOrSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/)
