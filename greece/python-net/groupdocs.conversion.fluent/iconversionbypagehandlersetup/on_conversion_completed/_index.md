---
title: "μέθοδος on_conversion_completed"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Καταχωρεί μια κλήση επιστροφής που θα κληθεί όταν η μετατροπή σελίδας ολοκληρωθεί επιτυχώς."
type: docs
url: /el/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersetup/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#on_completed}

Καταχωρεί μια κλήση επιστροφής που θα κληθεί όταν η μετατροπή σελίδας ολοκληρωθεί επιτυχώς.

```python
def on_conversion_completed(self, on_completed):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| on_completed | `Action[ConvertedPageContext]` | Μία ενέργεια για τη διαχείριση της ολοκλήρωσης, λαμβάνοντας το περιεχόμενο της μετατρεπόμενης σελίδας. |

**Returns:** Interface to continue conversion building, allowing only OnConversionFailed or Convert/Compress.

### Δείτε επίσης
* class [`IConversionByPageHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersetup/)
