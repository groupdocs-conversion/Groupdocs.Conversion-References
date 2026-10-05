---
title: "μέθοδος on_conversion_completed"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Καταχωρεί μια κλήση επιστροφής που θα κληθεί όταν η μετατροπή σελίδας ολοκληρωθεί επιτυχώς."
type: docs
url: /el/python-net/groupdocs.conversion.fluent/iconversionbypagehandlerfailed/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#on_completed}

Καταχωρεί μια κλήση επιστροφής που θα κληθεί όταν η μετατροπή σελίδας ολοκληρωθεί επιτυχώς.

Η επανεκκίνηση αντικαθιστά οποιονδήποτε προηγουμένως ορισμένο χειριστή.

```python
def on_conversion_completed(self, on_completed):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| on_completed | `Action[ConvertedPageContext]` | Μία ενέργεια για τη διαχείριση της ολοκλήρωσης, λαμβάνοντας το περιεχόμενο της μετατρεπόμενης σελίδας. |

**Returns:** This stage, so additional handlers or `Convert` / `Compress` may be chained.

### Δείτε επίσης
* class [`IConversionByPageHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlerfailed/)
