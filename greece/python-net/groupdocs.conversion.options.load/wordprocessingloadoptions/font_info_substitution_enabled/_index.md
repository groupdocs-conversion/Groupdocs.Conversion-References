---
title: "ιδιότητα font_info_substitution_enabled"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Η σημαία που ενεργοποιεί την αυτόματη αντικατάσταση των ελλιπών γραμματοσειρών βάσει του FontInfo στο έγγραφο."
type: docs
url: /el/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_info_substitution_enabled/
is_root: false
weight: 2120
---


## font_info_substitution_enabled property

Η σημαία που ενεργοποιεί την αυτόματη αντικατάσταση των ελλιπών γραμματοσειρών βάσει του FontInfo στο έγγραφο. Προεπιλογή: False.

Σημείωση: Η σειρά αντικατάστασης είναι η εξής:
- Automatically substitute missing fonts based on font name (if enabled).
- Automatically substitute missing fonts based on FontConfig (if enabled).
- Substitute missing fonts based on FontSubstitutes (if set).
- Automatically substitute missing fonts based on FontInfo (if enabled).
- Substitute missing fonts based on DefaultFont (if set).

### Definition:
```python
@property
def font_info_substitution_enabled(self):
    ...
@font_info_substitution_enabled.setter
def font_info_substitution_enabled(self, value):
    ...
```

### Δείτε επίσης
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
