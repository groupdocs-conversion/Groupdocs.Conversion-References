---
title: "convert_by_page_to μέθοδος"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Αποθήκευση μετατρεπόμενης σελίδας ως ροή."
type: docs
url: /el/python-net/groupdocs.conversion.fluent/iconversionto/convert_by_page_to/
is_root: false
weight: 1010
---


## convert_by_page_to {#converted_stream_provider}

Αποθήκευση μετατρεπόμενης σελίδας ως ροή.

```python
def convert_by_page_to(self, converted_stream_provider):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| converted_stream_provider | `Func[SavePageContext, io.RawIOBase]` | Πάροχος ροής σελίδας μετατρεπόμενου εγγράφου. converted_stream_provider arg1arg1: Το πλαίσιο αποθήκευσης. |

**Returns:** Page options or handler setup interface to continue conversion building.

### Δείτε επίσης
* class [`IConversionTo`](/conversion/python-net/groupdocs.conversion.fluent/iconversionto/)
