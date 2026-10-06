---
title: "метод crop"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Создаёт обрезанную версию текущего Rectangle, удаляя указанные отступы."
type: docs
url: /ru/python-net/groupdocs.conversion.contracts/rectangle/crop/
is_root: false
weight: 1010
---


## crop {#crop_left-crop_top-crop_right-crop_bottom}

Создаёт обрезанную версию текущего Rectangle, удаляя указанные отступы.

```python
def crop(self, crop_left, crop_top, crop_right, crop_bottom):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| crop_left | `int` | Количество пикселей, которое нужно удалить с левой стороны. |
| crop_top | `int` | Количество пикселей, которое нужно удалить с верхней стороны. |
| crop_right | `int` | Количество пикселей, которое нужно удалить с правой стороны. |
| crop_bottom | `int` | Количество пикселей, которое нужно удалить с нижней стороны. |

**Returns:** Rectangle: A new cropped rectangle.

### См. также
* class [`Rectangle`](/conversion/python-net/groupdocs.conversion.contracts/rectangle/)
