---
title: "ιδιότητα layout_scope"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Η layout scope που καθορίζει ποιοι χώροι σχεδίασης μετατρέπονται."
type: docs
url: /el/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_scope/
is_root: false
weight: 2070
---


## layout_scope property

Το πεδίο διάταξης που καθορίζει ποιοι χώροι σχεδίασης μετατρέπονται. Προεπιλογή είναι το [`CadLayoutScope.both`](/conversion/python-net/groupdocs.conversion.options.load/cadlayoutscope/), το οποίο δεν περιορίζει τη μετατροπή. Αγνοείται όταν παρέχεται το [`CadLoadOptions.layout_names`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/), επειδή τα ρητά ονόματα διάταξης πάντα προτιμώνται. Μια τιμή `None` αντιμετωπίζεται ως [`CadLayoutScope.both`](/conversion/python-net/groupdocs.conversion.options.load/cadlayoutscope/).

Εάν η scope δεν επιλέγει κανένα από τα φύλλα που προσφέρει ένα drawing, η μετατροπή αποτυγχάνει με `InvalidLoadOptionsException`, το οποίο ονομάζει τη scope και τα διαθέσιμα φύλλα αντί να αποδίδει τους εξαιρούμενους χώρους. Ένα drawing που δεν προσφέρει καθόλου φύλλο δεν επηρεάζεται και εξακολουθεί να μετατρέπεται ως μία ενιαία μονάδα. Δεν τηρείται κατά τη μετατροπή σε PDF/UA-1, για τον λόγο που αναφέρεται στο [`CadLoadOptions.layout_names`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/).

### Definition:
```python
@property
def layout_scope(self):
    ...
@layout_scope.setter
def layout_scope(self, value):
    ...
```

### Δείτε επίσης
* class [`CadLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/)
