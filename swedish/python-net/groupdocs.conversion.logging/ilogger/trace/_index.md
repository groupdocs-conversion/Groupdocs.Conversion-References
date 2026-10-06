---
title: "trace metod"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Skriver ett spårningsmeddelande i loggen som ger allmänt användbar information om applikationsflödet."
type: docs
url: /sv/python-net/groupdocs.conversion.logging/ilogger/trace/
is_root: false
weight: 1040
---


## trace {#message}

Skriver ett spårningsmeddelande i loggen som ger allmänt användbar information om applikationsflödet.

```python
def trace(self, message):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| message | `str` | Spårningsmeddelandet. |

### Exempel

```python
from groupdocs.conversion.logging import ConsoleLogger

logger = ConsoleLogger()
logger.trace("Conversion started")
```

### Se även
* class [`ILogger`](/conversion/python-net/groupdocs.conversion.logging/ilogger/)
