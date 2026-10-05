---
title: "convert_to μέθοδος"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Αποθήκευση μετατρεπόμενου εγγράφου ως αρχείο."
type: docs
url: /el/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/convert_to/
is_root: false
weight: 1030
---


## convert_to {#file_name}

Αποθήκευση μετατρεπόμενου εγγράφου ως αρχείο.

```python
def convert_to(self, file_name):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_name | `str` | Μετατρεπόμενο έγγραφο. |

**Returns:** Options or handler setup interface to continue conversion building.

## convert_to {#converted_stream_provider}

Αποθηκεύει το μετατρεπόμενο έγγραφο ως ροή.

```python
def convert_to(self, converted_stream_provider):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| converted_stream_provider | `Func[SaveContext, io.RawIOBase]` | Πάροχος ροής μετατρεπόμενου εγγράφου. Το πλαίσιο αποθήκευσης. |

**Returns:** Options or handler setup interface to continue conversion building.

### Δείτε επίσης
* class [`IConversionLoadOptionsOrSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/)
