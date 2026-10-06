---
title: "метод get_all_possible_conversions"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Получает все поддерживаемые преобразования."
type: docs
url: /ru/python-net/groupdocs.conversion/converter/get_all_possible_conversions/
is_root: false
weight: 1070
---


## get_all_possible_conversions

Получает все поддерживаемые преобразования.

Узнайте больше о поддерживаемых преобразованиях:
- [Full list of supported conversions](https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats)
- [How to get supported conversions in code](https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)

```python
def get_all_possible_conversions(cls):
    ...
```

**Returns:** Collection of all possible conversions.

### Пример

```python
from groupdocs.conversion import Converter

# Получить все возможные преобразования
all_conversions = list(Converter.get_all_possible_conversions())
print(f"Total supported source formats: {len(all_conversions)}")
```

### См. также
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
