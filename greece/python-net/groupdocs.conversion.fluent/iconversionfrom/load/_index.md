---
title: "μέθοδος load"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Ορίζει το όνομα αρχείου του πηγαίου εγγράφου."
type: docs
url: /el/python-net/groupdocs.conversion.fluent/iconversionfrom/load/
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

Ορίζει τον πίνακα πηγαίων εγγράφων.

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
| document_stream_provider | `Func[io.RawIOBase]` | Πάροχος ροής πηγαίου εγγράφου. |

| Εγείρει | Περιγραφή |
| :- | :- |
| `InvalidConverterSettingsException` | Εάν η επικύρωση των ρυθμίσεων του μετατροπέα αποτύχει. |

## load {#document_stream_provider}

Ορίζει τον πάροχο ροών πηγαίου εγγράφου.

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
* class [`IConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionfrom/)
