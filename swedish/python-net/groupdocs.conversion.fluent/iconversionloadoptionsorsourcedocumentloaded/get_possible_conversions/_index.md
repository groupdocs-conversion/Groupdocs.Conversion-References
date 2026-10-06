---
title: "get_possible_conversions‑metod"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Hämtar möjliga konverteringar för källdokumentet."
type: docs
url: /sv/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/get_possible_conversions/
is_root: false
weight: 1080
---


## get_possible_conversions

Hämtar möjliga konverteringar för källdokumentet.

Det returnerade objektet ger åtkomst till alla konverteringsalternativ, inklusive primära och sekundära format, och innehåller metadata om källfilen.

```python
def get_possible_conversions(self):
    ...
```

**Returns:** GroupDocs.Conversion.Fluent.PossibleConversions: An object containing the source description and collections of conversion formats.

### Exempel

```python
from groupdocs.conversion import Converter

with Converter("report.xlsx") as converter:
    conversions = converter.get_possible_conversions()
    primary = [c.format for c in conversions.all if c.is_primary]
    print(f"Primary targets for {conversions.source.description}: {primary}")
```

### Se även
* class [`IConversionLoadOptionsOrSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/)
