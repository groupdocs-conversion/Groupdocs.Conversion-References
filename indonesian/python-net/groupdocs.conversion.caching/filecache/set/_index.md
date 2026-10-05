---
title: "metode set"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Menyisipkan entri cache ke dalam cache."
type: docs
url: /id/python-net/groupdocs.conversion.caching/filecache/set/
is_root: false
weight: 1040
---


## set {#key-value}

Menyisipkan entri cache ke dalam cache.

```python
def set(self, key, value):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| key | `str` | Pengidentifikasi unik untuk entri cache. |
| value | `Any` | Objek yang akan disisipkan. |

### Contoh

```python
from groupdocs.conversion import ConverterSettings, FileCache

# Buat pengaturan konverter dengan cache berbasis file
settings = ConverterSettings()
settings.cache = FileCache()

# Simpan objek dalam cache
settings.cache.set("my_document", document)
```

### Lihat Juga
* class [`FileCache`](/conversion/python-net/groupdocs.conversion.caching/filecache/)
