---
title: "méthode set"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Insère une entrée de cache dans le cache."
type: docs
url: /fr/python-net/groupdocs.conversion.caching/filecache/set/
is_root: false
weight: 1040
---


## set {#key-value}

Insère une entrée de cache dans le cache.

```python
def set(self, key, value):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| key | `str` | Un identifiant unique pour l'entrée du cache. |
| value | `Any` | L'objet à insérer. |

### Exemple

```python
from groupdocs.conversion import ConverterSettings, FileCache

# Créer des paramètres de convertisseur avec un cache basé sur des fichiers
settings = ConverterSettings()
settings.cache = FileCache()

# Stocker un objet dans le cache
settings.cache.set("my_document", document)
```

### Voir aussi
* class [`FileCache`](/conversion/python-net/groupdocs.conversion.caching/filecache/)
