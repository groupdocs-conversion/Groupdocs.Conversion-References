---
title: "trace yöntemi"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Uygulama akışı hakkında genellikle faydalı bilgiler sağlayan bir izleme günlüğü mesajı yazar."
type: docs
url: /tr/python-net/groupdocs.conversion.logging/ilogger/trace/
is_root: false
weight: 1040
---


## trace {#message}

Uygulama akışı hakkında genellikle faydalı bilgiler sağlayan bir izleme günlüğü mesajı yazar.

```python
def trace(self, message):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| message | `str` | İzleme mesajı. |

### Örnek

```python
from groupdocs.conversion.logging import ConsoleLogger

logger = ConsoleLogger()
logger.trace("Conversion started")
```

### Ayrıca Bakınız
* class [`ILogger`](/conversion/python-net/groupdocs.conversion.logging/ilogger/)
