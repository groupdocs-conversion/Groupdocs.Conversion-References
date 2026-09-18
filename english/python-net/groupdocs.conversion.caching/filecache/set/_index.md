---
title: set method
second_title: GroupDocs.Conversion for Python via .NET API References
description: "Inserts a cache entry into the cache."
type: docs
url: /python-net/groupdocs.conversion.caching/filecache/set/
is_root: false
weight: 1040
---


## set {#key-value}

Inserts a cache entry into the cache.

```python
def set(self, key, value):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| key | `str` | A unique identifier for the cache entry. |
| value | `Any` | The object to insert. |

### Example

```python
from groupdocs.conversion import ConverterSettings, FileCache

# Create converter settings with a file-based cache
settings = ConverterSettings()
settings.cache = FileCache()

# Store an object in the cache
settings.cache.set("my_document", document)
```

### See Also
* class [`FileCache`](/conversion/python-net/groupdocs.conversion.caching/filecache/)
