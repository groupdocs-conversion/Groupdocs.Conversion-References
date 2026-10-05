---
title: "μέθοδος on_conversion_completed"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Καταχωρεί μια κλήση επιστροφής που θα κληθεί όταν η μετατροπή εγγράφου ολοκληρωθεί επιτυχώς."
type: docs
url: /el/python-net/groupdocs.conversion.fluent/iconversionhandlersetup/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#on_completed}

Καταχωρεί μια κλήση επιστροφής που θα κληθεί όταν η μετατροπή εγγράφου ολοκληρωθεί επιτυχώς.

```python
def on_conversion_completed(self, on_completed):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| on_completed | `Action[ConvertedContext]` | Μια ενέργεια για τη διαχείριση της ολοκλήρωσης, λαμβάνοντας το πλαίσιο μετατροπής. |

**Returns:** Interface to continue conversion building, allowing only OnConversionFailed or Convert/Compress.

### Δείτε επίσης
* class [`IConversionHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersetup/)
