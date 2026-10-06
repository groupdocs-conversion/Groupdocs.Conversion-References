---
title: "metodo set"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Inserisce una voce nella cache."
type: docs
url: /it/python-net/groupdocs.conversion.caching/filecache/set/
is_root: false
weight: 1040
---


## set {#key-value}

Inserisce una voce nella cache.

```python
def set(self, key, value):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| key | `str` | Un identificatore univoco per la voce della cache. |
| value | `Any` | L'oggetto da inserire. |

### Esempio

```python
from groupdocs.conversion import ConverterSettings, FileCache

# Crea impostazioni del convertitore con una cache basata su file
settings = ConverterSettings()
settings.cache = FileCache()

# Memorizza un oggetto nella cache
settings.cache.set("my_document", document)
```

### Vedi anche
* class [`FileCache`](/conversion/python-net/groupdocs.conversion.caching/filecache/)
