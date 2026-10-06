---
title: "trace metodo"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Scrive un messaggio di log di traccia che fornisce informazioni generalmente utili sul flusso dell'applicazione."
type: docs
url: /it/python-net/groupdocs.conversion.logging/ilogger/trace/
is_root: false
weight: 1040
---


## trace {#message}

Scrive un messaggio di log di traccia che fornisce informazioni generalmente utili sul flusso dell'applicazione.

```python
def trace(self, message):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| message | `str` | Il messaggio di traccia. |

### Esempio

```python
from groupdocs.conversion.logging import ConsoleLogger

logger = ConsoleLogger()
logger.trace("Conversion started")
```

### Vedi anche
* class [`ILogger`](/conversion/python-net/groupdocs.conversion.logging/ilogger/)
