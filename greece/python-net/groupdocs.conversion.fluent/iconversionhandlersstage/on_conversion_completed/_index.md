---
title: "μέθοδος on_conversion_completed"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Καταχωρεί μια κλήση επιστροφής που θα εκτελείται όταν μια μετατροπή εγγράφου ολοκληρωθεί επιτυχώς, αντικαθιστώντας οποιονδήποτε προηγουμένως ορισμένο χειριστή κατά την επανεκτέλεση."
type: docs
url: /el/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#on_completed}

Καταχωρεί μια κλήση επιστροφής που θα εκτελείται όταν μια μετατροπή εγγράφου ολοκληρωθεί επιτυχώς, αντικαθιστώντας οποιονδήποτε προηγουμένως ορισμένο χειριστή κατά την επανεκτέλεση.

```python
def on_conversion_completed(self, on_completed):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| on_completed | `Action[ConvertedContext]` | Μια ενέργεια για τη διαχείριση της ολοκλήρωσης, λαμβάνοντας το πλαίσιο μετατροπής. |

**Returns:** This stage, so additional handlers or `Convert` / `Compress` may be chained. Returns `IConversionHandlersStage`.

### Δείτε επίσης
* class [`IConversionHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/)
