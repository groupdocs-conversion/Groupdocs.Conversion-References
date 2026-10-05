---
title: "μέθοδος set"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Εισάγει μια καταχώρηση cache στην κρυφή μνήμη."
type: docs
url: /el/python-net/groupdocs.conversion.caching/filecache/set/
is_root: false
weight: 1040
---


## set {#key-value}

Εισάγει μια καταχώρηση cache στην κρυφή μνήμη.

```python
def set(self, key, value):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| key | `str` | Ένα μοναδικό αναγνωριστικό για την καταχώριση της κρυφής μνήμης. |
| value | `Any` | Το αντικείμενο για εισαγωγή. |

### Παράδειγμα

```python
from groupdocs.conversion import ConverterSettings, FileCache

# Δημιουργήστε ρυθμίσεις μετατροπέα με κρυφή μνήμη που βασίζεται σε αρχείο
settings = ConverterSettings()
settings.cache = FileCache()

# Αποθηκεύστε ένα αντικείμενο στην κρυφή μνήμη
settings.cache.set("my_document", document)
```

### Δείτε επίσης
* class [`FileCache`](/conversion/python-net/groupdocs.conversion.caching/filecache/)
