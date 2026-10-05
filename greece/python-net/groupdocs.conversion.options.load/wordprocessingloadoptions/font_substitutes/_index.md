---
title: "ιδιότητα font_substitutes"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Οι υποκατάστατες γραμματοσειρές που χρησιμοποιούνται κατά τη μετατροπή ενός εγγράφου WordProcessing."
type: docs
url: /el/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_substitutes/
is_root: false
weight: 2140
---


## font_substitutes property

Οι υποκατάστατες γραμματοσειρές που χρησιμοποιούνται κατά τη μετατροπή ενός εγγράφου WordProcessing.

Σημείωση: Η σειρά αντικατάστασης είναι η εξής:

- 1) Automatically substitute missing fonts based on font name (if enabled).
- 2) Automatically substitute missing fonts based on FontConfig (if enabled).
- 3) Substitute missing fonts based on FontSubstitutes (if set).
- 4) Automatically substitute missing fonts based on FontInfo (if enabled).
- 5) Substitute missing fonts based on DefaultFont (if set).

### Definition:
```python
@property
def font_substitutes(self):
    ...
@font_substitutes.setter
def font_substitutes(self, value):
    ...
```

### Δείτε επίσης
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
