---
title: "конструктор __init__"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Инициализирует экземпляр WatermarkTextOptions с указанным текстом водяного знака."
type: docs
url: /ru/python-net/groupdocs.conversion.options.convert/watermarktextoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#text}

Инициализирует экземпляр WatermarkTextOptions с указанным текстом водяного знака.

```python
def __init__(self, text):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| text | `str` | Текст, который будет использоваться в качестве водяного знака. |

### Пример

```python
from groupdocs.conversion.options.convert import WatermarkTextOptions

# Создайте водяной знак с текстом "DRAFT"
watermark = WatermarkTextOptions("DRAFT")
```

### См. также
* class [`WatermarkTextOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarktextoptions/)
