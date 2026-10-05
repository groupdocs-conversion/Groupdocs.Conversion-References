---
title: "ιδιότητα font_config_substitution_enabled"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Η ιδιότητα ενεργοποιεί την αυτόματη αντικατάσταση των ελλιπών γραμματοσειρών βάσει του συστήματος FontConfig."
type: docs
url: /el/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_config_substitution_enabled/
is_root: false
weight: 2110
---


## font_config_substitution_enabled property

Η ιδιότητα ενεργοποιεί την αυτόματη αντικατάσταση των ελλιπών γραμματοσειρών βάσει του συστημικού FontConfig. Η προεπιλογή είναι False.

Σημείωση: Η σειρά αντικατάστασης είναι η εξής:
- Automatically substitute missing fonts based on font name (if enabled).
- Automatically substitute missing fonts based on FontConfig (if enabled).
- Substitute missing fonts based on FontSubstitutes (if set).
- Automatically substitute missing fonts based on FontInfo (if enabled).
- Substitute missing fonts based on DefaultFont (if set).

### Definition:
```python
@property
def font_config_substitution_enabled(self):
    ...
@font_config_substitution_enabled.setter
def font_config_substitution_enabled(self, value):
    ...
```

### Δείτε επίσης
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
