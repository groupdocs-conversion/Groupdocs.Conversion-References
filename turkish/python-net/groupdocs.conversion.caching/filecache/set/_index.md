---
title: "set metodu"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Önbelleğe bir önbellek girdisi ekler."
type: docs
url: /tr/python-net/groupdocs.conversion.caching/filecache/set/
is_root: false
weight: 1040
---


## set {#key-value}

Önbelleğe bir önbellek girdisi ekler.

```python
def set(self, key, value):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| key | `str` | Önbellek girişi için benzersiz bir tanımlayıcı. |
| value | `Any` | Eklenecek nesne. |

### Örnek

```python
from groupdocs.conversion import ConverterSettings, FileCache

# Dosya tabanlı önbellekle dönüştürücü ayarları oluştur
settings = ConverterSettings()
settings.cache = FileCache()

# Bir nesneyi önbellekte sakla
settings.cache.set("my_document", document)
```

### Ayrıca Bakınız
* class [`FileCache`](/conversion/python-net/groupdocs.conversion.caching/filecache/)
