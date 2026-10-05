---
title: "Méthode trace"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Écrit un message de journal de trace fournissant des informations généralement utiles sur le flux de l'application."
type: docs
url: /fr/python-net/groupdocs.conversion.logging/ilogger/trace/
is_root: false
weight: 1040
---


## trace {#message}

Écrit un message de journal de trace fournissant des informations généralement utiles sur le flux de l'application.

```python
def trace(self, message):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| message | `str` | Le message de trace. |

### Exemple

```python
from groupdocs.conversion.logging import ConsoleLogger

logger = ConsoleLogger()
logger.trace("Conversion started")
```

### Voir aussi
* class [`ILogger`](/conversion/python-net/groupdocs.conversion.logging/ilogger/)
