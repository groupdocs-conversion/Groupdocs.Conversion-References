---
title: "μέθοδος load"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Ορίζει το όνομα αρχείου του πηγαίου εγγράφου."
type: docs
url: /el/python-net/groupdocs.conversion.fluent/iconversionsettingsorconversionfrom/load/
is_root: false
weight: 1010
---


## load {#file_name}

Ορίζει το όνομα αρχείου του πηγαίου εγγράφου.

```python
def load(self, file_name):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_name | `str` | Πηγαίο έγγραφο. |

## load {#file_name}

Ορίστε τον πίνακα πηγών εγγράφων.

```python
def load(self, file_name):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_name | `list[str]` | Σύνολο πηγαίων εγγράφων. |

## load {#document_stream_provider}

Ορίστε τη ροή του πηγαίου εγγράφου.

```python
def load(self, document_stream_provider):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| document_stream_provider | `Func[io.RawIOBase]` | Πάροχος ρεύματος πηγής εγγράφου |

| Εγείρει | Περιγραφή |
| :- | :- |
| `InvalidConverterSettingsException` | Εάν η επικύρωση των ρυθμίσεων του μετατροπέα αποτύχει, αυτή η εξαίρεση θα ριχτεί |

## load {#document_stream_provider}

Ορίστε τον πίνακα ροών πηγών εγγράφων.

```python
def load(self, document_stream_provider):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| document_stream_provider | `Func[list[io.RawIOBase]]` | Πάροχος ροών πηγαίου εγγράφου. |

| Εγείρει | Περιγραφή |
| :- | :- |
| `InvalidConverterSettingsException` | Εάν η επικύρωση των ρυθμίσεων του μετατροπέα αποτύχει. |

### Δείτε επίσης
* class [`IConversionSettingsOrConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettingsorconversionfrom/)
