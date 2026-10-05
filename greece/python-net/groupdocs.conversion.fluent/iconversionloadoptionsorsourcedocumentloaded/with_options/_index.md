---
title: "μέθοδος with_options"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Ορίστε επιλογές φόρτωσης."
type: docs
url: /el/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/with_options/
is_root: false
weight: 1100
---


## with_options {#load_options}

Ορίστε επιλογές φόρτωσης.

```python
def with_options(self, load_options):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| load_options | `LoadOptions` | Επιλογές φόρτωσης |

## with_options {#load_options_provider}

Παρέχει επιλογές φόρτωσης για το έγγραφο που φορτώνεται αυτή τη στιγμή.

```python
def with_options(self, load_options_provider):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| load_options_provider | `Func[LoadContext, LoadOptions]` | Πάροχος επιλογών φόρτωσης. Το πλαίσιο επιλογών φόρτωσης. |

### Δείτε επίσης
* class [`IConversionLoadOptionsOrSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/)
