---
title: "метод get_possible_conversions"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Получает возможные преобразования исходного документа."
type: docs
url: /ru/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/get_possible_conversions/
is_root: false
weight: 1080
---


## get_possible_conversions

Получает возможные преобразования исходного документа.

Возвращаемый объект предоставляет доступ ко всем параметрам преобразования, включая основные и вторичные форматы, и содержит метаданные о исходном файле.

```python
def get_possible_conversions(self):
    ...
```

**Returns:** GroupDocs.Conversion.Fluent.PossibleConversions: An object containing the source description and collections of conversion formats.

### Пример

```python
from groupdocs.conversion import Converter

with Converter("report.xlsx") as converter:
    conversions = converter.get_possible_conversions()
    primary = [c.format for c in conversions.all if c.is_primary]
    print(f"Primary targets for {conversions.source.description}: {primary}")
```

### См. также
* class [`IConversionLoadOptionsOrSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/)
