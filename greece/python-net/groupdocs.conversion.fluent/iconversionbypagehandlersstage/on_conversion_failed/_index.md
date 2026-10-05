---
title: "on_conversion_failed μέθοδος"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Καταχωρεί μια κλήση επιστροφής που θα κληθεί όταν η μετατροπή μιας σελίδας αποτύχει, αντικαθιστώντας οποιονδήποτε προηγουμένως ορισμένο χειριστή κατά την επανεκκίνηση."
type: docs
url: /el/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/on_conversion_failed/
is_root: false
weight: 1060
---


## on_conversion_failed {#on_failed}

Καταχωρεί μια κλήση επιστροφής που θα κληθεί όταν η μετατροπή μιας σελίδας αποτύχει, αντικαθιστώντας οποιονδήποτε προηγουμένως ορισμένο χειριστή κατά την επανεκκίνηση.

```python
def on_conversion_failed(self, on_failed):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| on_failed | `Action[ConvertedPageContext, Exception]` | Κλήσιμη (callable) που διαχειρίζεται την αποτυχία, λαμβάνοντας το περιεχόμενο της μετατρεπόμενης σελίδας και την εξαίρεση που προκάλεσε την αποτυχία. |

**Returns:** IConversionByPageHandlersStage: This stage, so additional handlers or `Convert` / `Compress` may be chained.

### Δείτε επίσης
* class [`IConversionByPageHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/)
