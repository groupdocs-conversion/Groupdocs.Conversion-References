---
title: "μέθοδος with_options"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Ορίζει επιλογές μετατροπής για τη διαδικασία μετατροπής."
type: docs
url: /el/python-net/groupdocs.conversion.fluent/iconversionoptionsonly/with_options/
is_root: false
weight: 1010
---


## with_options {#convert_options}

Ορίζει επιλογές μετατροπής για τη διαδικασία μετατροπής.

```python
def with_options(self, convert_options):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| convert_options | `ConvertOptions` | Επιλογές μετατροπής. |

**Returns:** Handler setup interface to continue conversion building.

## with_options {#options_provider}

Ορίζει επιλογές μετατροπής χρησιμοποιώντας μια συνάρτηση παρόχου.

```python
def with_options(self, options_provider):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| options_provider | `Func[ConvertContext, ConvertOptions]` | Μια συνάρτηση που παρέχει επιλογές μετατροπής βάσει του πλαισίου μετατροπής. |

**Returns:** Handler setup interface to continue conversion building.

### Δείτε επίσης
* class [`IConversionOptionsOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionoptionsonly/)
