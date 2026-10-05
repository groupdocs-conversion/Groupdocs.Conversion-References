---
title: "on_conversion_failed μέθοδος"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Καταχωρεί μια κλήση επιστροφής που θα κληθεί όταν η μετατροπή σελίδας αποτύχει."
type: docs
url: /el/python-net/groupdocs.conversion.fluent/iconversionbypagehandlerfailed/on_conversion_failed/
is_root: false
weight: 1060
---


## on_conversion_failed {#on_failed}

Καταχωρεί μια κλήση επιστροφής που θα κληθεί όταν η μετατροπή σελίδας αποτύχει.

```python
def on_conversion_failed(self, on_failed):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| on_failed | `Action[ConvertedPageContext, Exception]` | Μία ενέργεια για τη διαχείριση της αποτυχίας, λαμβάνοντας το περιεχόμενο της μετατρεπόμενης σελίδας και την εξαίρεση που προκάλεσε την αποτυχία. |

**Returns:** The flat by-page handlers stage, so additional handlers or `Convert`/`Compress` may be chained.

### Δείτε επίσης
* class [`IConversionByPageHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlerfailed/)
