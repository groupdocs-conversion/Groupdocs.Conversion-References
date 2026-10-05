---
title: "Metode trace"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Menulis pesan log jejak yang menyediakan informasi umum yang berguna tentang alur aplikasi."
type: docs
url: /id/python-net/groupdocs.conversion.logging/ilogger/trace/
is_root: false
weight: 1040
---


## trace {#message}

Menulis pesan log jejak yang menyediakan informasi umum yang berguna tentang alur aplikasi.

```python
def trace(self, message):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| message | `str` | Pesan trace. |

### Contoh

```python
from groupdocs.conversion.logging import ConsoleLogger

logger = ConsoleLogger()
logger.trace("Conversion started")
```

### Lihat Juga
* class [`ILogger`](/conversion/python-net/groupdocs.conversion.logging/ilogger/)
