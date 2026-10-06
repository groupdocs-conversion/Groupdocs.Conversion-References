---
title: "Метод trace"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Записывает трассировочное сообщение журнала, предоставляющее общую полезную информацию о потоке приложения."
type: docs
url: /ru/python-net/groupdocs.conversion.logging/ilogger/trace/
is_root: false
weight: 1040
---


## trace {#message}

Записывает трассировочное сообщение журнала, предоставляющее общую полезную информацию о потоке приложения.

```python
def trace(self, message):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| message | `str` | Сообщение трассировки. |

### Пример

```python
from groupdocs.conversion.logging import ConsoleLogger

logger = ConsoleLogger()
logger.trace("Conversion started")
```

### См. также
* class [`ILogger`](/conversion/python-net/groupdocs.conversion.logging/ilogger/)
