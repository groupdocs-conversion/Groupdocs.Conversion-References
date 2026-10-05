---
title: "image_saving_callback ιδιότητα"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Η κλήση επιστροφής που εκτελείται μία φορά ανά εικόνα κατά την αποθήκευση του Markdown."
type: docs
url: /el/python-net/groupdocs.conversion.options.convert/markdownoptions/image_saving_callback/
is_root: false
weight: 2020
---


## image_saving_callback property

Η κλήση επιστροφής που καλείται μία φορά ανά εικόνα κατά την αποθήκευση του Markdown. Επιτρέπει στον καλούντα να διατηρεί τις εικόνες εξωτερικά και να αντικαθιστά το URI που είναι ενσωματωμένο στο έγγραφο. Έχει προτεραιότητα έναντι του [`MarkdownOptions.export_images_as_base64`](/conversion/python-net/groupdocs.conversion.options.convert/markdownoptions/export_images_as_base64/) όταν δεν είναι None.

### Definition:
```python
@property
def image_saving_callback(self):
    ...
@image_saving_callback.setter
def image_saving_callback(self, value):
    ...
```

### Δείτε επίσης
* class [`MarkdownOptions`](/conversion/python-net/groupdocs.conversion.options.convert/markdownoptions/)
