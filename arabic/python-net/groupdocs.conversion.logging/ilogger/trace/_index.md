---
title: "طريقة trace"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "يكتب رسالة سجل تتبع توفر معلومات عامة مفيدة حول تدفق التطبيق."
type: docs
url: /ar/python-net/groupdocs.conversion.logging/ilogger/trace/
is_root: false
weight: 1040
---


## trace {#message}

يكتب رسالة سجل تتبع توفر معلومات عامة مفيدة حول تدفق التطبيق.

```python
def trace(self, message):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| message | `str` | رسالة التتبع. |

### مثال

```python
from groupdocs.conversion.logging import ConsoleLogger

logger = ConsoleLogger()
logger.trace("Conversion started")
```

### انظر أيضًا
* class [`ILogger`](/conversion/python-net/groupdocs.conversion.logging/ilogger/)
