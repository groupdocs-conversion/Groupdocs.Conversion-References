---
title: "set-metod"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Infogar en cachepost i cachen."
type: docs
url: /sv/python-net/groupdocs.conversion.caching/filecache/set/
is_root: false
weight: 1040
---


## set {#key-value}

Infogar en cachepost i cachen.

```python
def set(self, key, value):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| key | `str` | En unik identifierare för cache-posten. |
| value | `Any` | Objektet att infoga. |

### Exempel

```python
from groupdocs.conversion import ConverterSettings, FileCache

# Skapa konverteringsinställningar med en filbaserad cache
settings = ConverterSettings()
settings.cache = FileCache()

# Lagra ett objekt i cachen
settings.cache.set("my_document", document)
```

### Se även
* class [`FileCache`](/conversion/python-net/groupdocs.conversion.caching/filecache/)
