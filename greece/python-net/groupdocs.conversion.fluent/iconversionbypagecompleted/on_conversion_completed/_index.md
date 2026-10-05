---
title: "μέθοδος on_conversion_completed"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Λαμβάνει τη ροή της μετατρεπόμενης σελίδας."
type: docs
url: /el/python-net/groupdocs.conversion.fluent/iconversionbypagecompleted/on_conversion_completed/
is_root: false
weight: 1010
---


## on_conversion_completed {#converted_page_stream}

Λαμβάνει τη ροή της μετατρεπόμενης σελίδας. Θα ενεργοποιηθεί μόνο εάν έχει οριστεί `ConvertTo(convertedStreamProvider)`.

```python
def on_conversion_completed(self, converted_page_stream):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| converted_page_stream | `Action[ConvertedPageContext]` | Πάροχος ροής μετατρεπόμενης σελίδας. Το `ConvertedPageContext`. |

**Returns:** Interface to continue conversion building.

### Δείτε επίσης
* class [`IConversionByPageCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagecompleted/)
