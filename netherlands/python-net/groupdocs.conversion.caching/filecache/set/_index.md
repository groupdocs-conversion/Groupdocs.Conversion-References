---
title: "set-methode"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Voegt een cache‑item toe aan de cache."
type: docs
url: /nl/python-net/groupdocs.conversion.caching/filecache/set/
is_root: false
weight: 1040
---


## set {#key-value}

Voegt een cache‑item toe aan de cache.

```python
def set(self, key, value):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| key | `str` | Een unieke identificatie voor de cache entry. |
| value | `Any` | Het object om in te voegen. |

### Voorbeeld

```python
from groupdocs.conversion import ConverterSettings, FileCache

# Maak converterinstellingen met een bestandgebaseerde cache
settings = ConverterSettings()
settings.cache = FileCache()

# Sla een object op in de cache
settings.cache.set("my_document", document)
```

### Zie ook
* class [`FileCache`](/conversion/python-net/groupdocs.conversion.caching/filecache/)
