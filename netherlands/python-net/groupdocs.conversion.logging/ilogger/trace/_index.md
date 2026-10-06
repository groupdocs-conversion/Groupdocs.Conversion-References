---
title: "trace methode"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Schrijft een traceerlogbericht dat over het algemeen nuttige informatie over de applicatiestroom biedt."
type: docs
url: /nl/python-net/groupdocs.conversion.logging/ilogger/trace/
is_root: false
weight: 1040
---


## trace {#message}

Schrijft een traceerlogbericht dat over het algemeen nuttige informatie over de applicatiestroom biedt.

```python
def trace(self, message):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| message | `str` | Het trace‑bericht. |

### Voorbeeld

```python
from groupdocs.conversion.logging import ConsoleLogger

logger = ConsoleLogger()
logger.trace("Conversion started")
```

### Zie ook
* class [`ILogger`](/conversion/python-net/groupdocs.conversion.logging/ilogger/)
