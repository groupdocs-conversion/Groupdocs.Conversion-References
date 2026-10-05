---
title: "trace μέθοδος"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Γράφει ένα μήνυμα καταγραφής εντοπισμού που παρέχει γενικά χρήσιμες πληροφορίες σχετικά με τη ροή της εφαρμογής."
type: docs
url: /el/python-net/groupdocs.conversion.logging/ilogger/trace/
is_root: false
weight: 1040
---


## trace {#message}

Γράφει ένα μήνυμα καταγραφής εντοπισμού που παρέχει γενικά χρήσιμες πληροφορίες σχετικά με τη ροή της εφαρμογής.

```python
def trace(self, message):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| message | `str` | Το μήνυμα εντοπισμού. |

### Παράδειγμα

```python
from groupdocs.conversion.logging import ConsoleLogger

logger = ConsoleLogger()
logger.trace("Conversion started")
```

### Δείτε επίσης
* class [`ILogger`](/conversion/python-net/groupdocs.conversion.logging/ilogger/)
