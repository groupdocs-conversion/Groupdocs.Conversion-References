---
title: "DocumentInfo κλάση"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Η βασική υλοποίηση για την ανάκτηση πολυμορφικών πληροφοριών εγγράφου."
type: docs
url: /el/python-net/groupdocs.conversion.contracts/documentinfo/
is_root: false
weight: 120
---


## DocumentInfo class

Η βασική υλοποίηση για την ανάκτηση πολυμορφικών πληροφοριών εγγράφου.

Οι παρουσίες επιστρέφονται από `Converter.get_document_info()` και εκθέτουν μεταδεδομένα όπως μορφή, αριθμός σελίδων, ημερομηνία δημιουργίας, μέγεθος και ιδιότητες‑συγκεκριμένες μορφής.

Η DocumentInfo τύπος εκθέτει τα παρακάτω μέλη:

### Μέθοδοι
| Μέθοδος | Περιγραφή |
| :- | :- |
| [get](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/get/) |  |
| [get_file](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/get_file/) |  |
| [get_string](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/get_string/) |  |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [creation_date](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/creation_date/) | Η ημερομηνία δημιουργίας του εγγράφου. |
| [format](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/format/) | Η μορφή του εγγράφου. |
| [pages_count](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/pages_count/) | Ο συνολικός αριθμός σελίδων στο έγγραφο. |
| [property_names](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/property_names/) | Η ιδιότητα υλοποιεί [`IDocumentInfo.property_names`](/conversion/python-net/groupdocs.conversion.contracts/idocumentinfo/property_names/). |
| [size](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/size/) | Το μέγεθος του εγγράφου σε byte. |

### Παράδειγμα

```python
from groupdocs.conversion import Converter

def show_document_info(path):
    with Converter(path) as converter:
        info = converter.get_document_info()
        print("Format:", info.format)
        print("Pages count:", info.pages_count)
        print("Creation date:", info.creation_date)
        print("Size (bytes):", info.size)

# Παράδειγμα χρήσης
show_document_info("./lorem-ipsum.txt")
```

### Δείτε επίσης
* module [`groupdocs.conversion.contracts`](/conversion/python-net/groupdocs.conversion.contracts/)
