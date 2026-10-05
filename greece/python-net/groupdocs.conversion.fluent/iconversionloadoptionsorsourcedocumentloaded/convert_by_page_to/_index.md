---
title: "convert_by_page_to μέθοδος"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Αποθηκεύει τη μετατρεπόμενη σελίδα ως ροή."
type: docs
url: /el/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/convert_by_page_to/
is_root: false
weight: 1010
---


## convert_by_page_to {#converted_stream_provider}

Αποθηκεύει τη μετατρεπόμενη σελίδα ως ροή.

```python
def convert_by_page_to(self, converted_stream_provider):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| converted_stream_provider | `Func[SavePageContext, io.RawIOBase]` | Πάροχος ροής σελίδας μετατρεπόμενου εγγράφου. |

**Returns:** Page options or handler setup interface to continue conversion building.

### Δείτε επίσης
* class [`IConversionLoadOptionsOrSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/)
