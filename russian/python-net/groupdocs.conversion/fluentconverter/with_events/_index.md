---
title: "метод with_events"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Запускает fluent‑цепочку на этапе входа с обработчиками событий жизненного цикла конвертации."
type: docs
url: /ru/python-net/groupdocs.conversion/fluentconverter/with_events/
is_root: false
weight: 1070
---


## with_events {#configure}

Запускает fluent‑цепочку на этапе входа с обработчиками событий жизненного цикла конвертации.

```python
def with_events(cls, configure):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| configure | `Action[ConversionEvents]` | Вызываемый объект, изменяющий набор `ConversionEvents`. |

**Returns:** The source-selection stage, allowing `Load` to be chained.

### См. также
* class [`FluentConverter`](/conversion/python-net/groupdocs.conversion/fluentconverter/)
