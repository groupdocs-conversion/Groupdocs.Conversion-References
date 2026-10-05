---
title: "μέθοδος on_conversion_completed"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Καταχωρεί μια κλήση επιστροφής που θα κληθεί όταν η μετατροπή μιας σελίδας ολοκληρωθεί επιτυχώς, αντικαθιστώντας οποιονδήποτε προηγουμένως ορισμένο χειριστή κατά την επανεκκίνηση."
type: docs
url: /el/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#on_completed}

Καταχωρεί μια κλήση επιστροφής που θα κληθεί όταν η μετατροπή μιας σελίδας ολοκληρωθεί επιτυχώς, αντικαθιστώντας οποιονδήποτε προηγουμένως ορισμένο χειριστή κατά την επανεκκίνηση.

```python
def on_conversion_completed(self, on_completed):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| on_completed | `Action[ConvertedPageContext]` | Μία ενέργεια για τη διαχείριση της ολοκλήρωσης, λαμβάνοντας το περιεχόμενο της μετατρεπόμενης σελίδας. |

**Returns:** This stage, so additional handlers or `Convert` / `Compress` may be chained.

### Δείτε επίσης
* class [`IConversionByPageHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/)
