---
title: "ιδιότητα keep_image_stream_open"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Η ιδιότητα καθορίζει αν ο μετατροπέας διατηρεί το ρεύμα εικόνας ανοιχτό μετά τη μετατροπή."
type: docs
url: /el/python-net/groupdocs.conversion.options.convert/markdownimagesavingargs/keep_image_stream_open/
is_root: false
weight: 2030
---


## keep_image_stream_open property

Η ιδιότητα καθορίζει αν ο μετατροπέας διατηρεί το ρεύμα εικόνας ανοιχτό μετά τη μετατροπή.

Όταν είναι False (προεπιλογή), ο μετατροπέας κλείνει [`MarkdownImageSavingArgs.image_stream`](/conversion/python-net/groupdocs.conversion.options.convert/markdownimagesavingargs/image_stream/) μετά τη γραφή — κάτι τυπικό για αντικαταστάσεις `io.RawIOBase` που πρέπει να αδειάσουν στο δίσκο. Ορίστε σε True για να διατηρήσετε τη ροή ανοιχτή μετά την ολοκλήρωση της μετατροπής (συνηθισμένο για ένα `io.BytesIO` που σκοπεύετε να διαβάσετε μόνοι σας); ο καλών τότε είναι υπεύθυνος για την απελευθέρωση.

### Definition:
```python
@property
def keep_image_stream_open(self):
    ...
@keep_image_stream_open.setter
def keep_image_stream_open(self, value):
    ...
```

### Δείτε επίσης
* class [`MarkdownImageSavingArgs`](/conversion/python-net/groupdocs.conversion.options.convert/markdownimagesavingargs/)
