---
title: "set-Methode"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Fügt einen Cache‑Eintrag in den Cache ein."
type: docs
url: /de/python-net/groupdocs.conversion.caching/filecache/set/
is_root: false
weight: 1040
---


## set {#key-value}

Fügt einen Cache‑Eintrag in den Cache ein.

```python
def set(self, key, value):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| key | `str` | Ein eindeutiger Bezeichner für den Cache-Eintrag. |
| value | `Any` | Das einzufügende Objekt. |

### Beispiel

```python
from groupdocs.conversion import ConverterSettings, FileCache

# Konvertereinstellungen mit dateibasiertem Cache erstellen
settings = ConverterSettings()
settings.cache = FileCache()

# Ein Objekt im Cache speichern
settings.cache.set("my_document", document)
```

### Siehe auch
* class [`FileCache`](/conversion/python-net/groupdocs.conversion.caching/filecache/)
