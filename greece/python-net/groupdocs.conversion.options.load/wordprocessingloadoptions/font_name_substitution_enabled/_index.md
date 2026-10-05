---
title: "font_name_substitution_enabled ιδιότητα"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Η ιδιότητα υποδεικνύει εάν οι ελλιπείς γραμματοσειρές αντικαθίστανται αυτόματα βάσει του ονόματος γραμματοσειράς."
type: docs
url: /el/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_name_substitution_enabled/
is_root: false
weight: 2130
---


## font_name_substitution_enabled property

Η ιδιότητα υποδεικνύει εάν οι ελλιπείς γραμματοσειρές αντικαθίστανται αυτόματα βάσει του ονόματος γραμματοσειράς. Προεπιλογή: False.

Σημείωση: Η σειρά αντικατάστασης είναι η εξής:

- Automatically substitute missing fonts based on font name (if enabled).
- Automatically substitute missing fonts based on FontConfig (if enabled).
- Substitute missing fonts based on FontSubstitutes (if set).
- Automatically substitute missing fonts based on FontInfo (if enabled).
- Substitute missing fonts based on DefaultFont (if set).

### Definition:
```python
@property
def font_name_substitution_enabled(self):
    ...
@font_name_substitution_enabled.setter
def font_name_substitution_enabled(self, value):
    ...
```

### Δείτε επίσης
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
