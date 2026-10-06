---
title: "método set"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Inserta una entrada en la caché."
type: docs
url: /es/python-net/groupdocs.conversion.caching/filecache/set/
is_root: false
weight: 1040
---


## set {#key-value}

Inserta una entrada en la caché.

```python
def set(self, key, value):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| key | `str` | Un identificador único para la entrada de caché. |
| value | `Any` | El objeto a insertar. |

### Ejemplo

```python
from groupdocs.conversion import ConverterSettings, FileCache

# Crear configuraciones del convertidor con una caché basada en archivos
settings = ConverterSettings()
settings.cache = FileCache()

# Almacenar un objeto en la caché
settings.cache.set("my_document", document)
```

### Ver también
* class [`FileCache`](/conversion/python-net/groupdocs.conversion.caching/filecache/)
