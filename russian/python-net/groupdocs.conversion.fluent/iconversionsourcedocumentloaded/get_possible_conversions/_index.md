---
title: "метод get_possible_conversions"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Получает возможные преобразования исходного документа."
type: docs
url: /ru/python-net/groupdocs.conversion.fluent/iconversionsourcedocumentloaded/get_possible_conversions/
is_root: false
weight: 1080
---


## get_possible_conversions

Получает возможные преобразования исходного документа.

```python
def get_possible_conversions(self):
    ...
```

### Пример

```python
from groupdocs.conversion import Converter

with Converter("report.xlsx") as converter:
    conversions = converter.get_possible_conversions()
    primary = [c.format for c in conversions.all if c.is_primary]
    print(f"Primary targets for {conversions.source.description}: {primary}")
```

### См. также
* class [`IConversionSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsourcedocumentloaded/)
