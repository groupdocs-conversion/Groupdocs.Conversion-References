---
title: "get_possible_conversions metodu"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Kaynak belge için olası dönüşümleri alır."
type: docs
url: /tr/python-net/groupdocs.conversion.fluent/iconversionsourcedocumentloaded/get_possible_conversions/
is_root: false
weight: 1080
---


## get_possible_conversions

Kaynak belge için olası dönüşümleri alır.

```python
def get_possible_conversions(self):
    ...
```

### Örnek

```python
from groupdocs.conversion import Converter

with Converter("report.xlsx") as converter:
    conversions = converter.get_possible_conversions()
    primary = [c.format for c in conversions.all if c.is_primary]
    print(f"Primary targets for {conversions.source.description}: {primary}")
```

### Ayrıca Bakınız
* class [`IConversionSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsourcedocumentloaded/)
