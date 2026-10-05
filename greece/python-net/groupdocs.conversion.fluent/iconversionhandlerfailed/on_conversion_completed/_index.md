---
title: "μέθοδος on_conversion_completed"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Καταχωρεί μια κλήση επιστροφής που θα κληθεί όταν η μετατροπή εγγράφου ολοκληρωθεί επιτυχώς."
type: docs
url: /el/python-net/groupdocs.conversion.fluent/iconversionhandlerfailed/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#on_completed}

Καταχωρεί μια κλήση επιστροφής που θα εκτελείται όταν μια μετατροπή εγγράφου ολοκληρωθεί επιτυχώς. Η επανεκτέλεση αντικαθιστά οποιονδήποτε προηγουμένως ορισμένο χειριστή.

```python
def on_conversion_completed(self, on_completed):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| on_completed | `Action[ConvertedContext]` | Κλήσιμο που διαχειρίζεται την ολοκλήρωση, λαμβάνοντας το πλαίσιο μετατροπής. |

**Returns:** The current stage, allowing additional handlers or `Convert` / `Compress` to be chained.

### Δείτε επίσης
* class [`IConversionHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlerfailed/)
