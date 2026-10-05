---
title: "ιδιότητα on_font_substituted"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Το συμβάν που ενεργοποιείται όταν μια γραμματοσειρά που αναφέρεται από το έγγραφο προέλευσης δεν είναι διαθέσιμη και αντικαθίσταται (είτε από έναν κανόνα FontSubstitute που παρέχεται από τον πελάτη, είτε από την προεπιλεγμένη γραμματοσειρά που έχει ρυθμιστεί, είτε από το…"
type: docs
url: /el/python-net/groupdocs.conversion/conversionevents/on_font_substituted/
is_root: false
weight: 2070
---


## on_font_substituted property

Το γεγονός ενεργοποιείται όταν μια γραμματοσειρά που αναφέρεται από το πηγαίο έγγραφο δεν είναι διαθέσιμη και αντικαθίσταται (είτε από έναν προσαρμοσμένο κανόνα [`FontSubstitute`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitute/), είτε από την προρυθμισμένη προεπιλεγμένη γραμματοσειρά, είτε από την εσωτερική εναλλακτική λύση της γραμμής μετατροπής).

Το συμβάν αφαιρεί διπλότυπα ανά `(SourceFileName, OriginalFontName)` μέσα σε μία κλήση `Converter.Convert(...)` — οι συνδρομητές λαμβάνουν το πολύ μία ειδοποίηση ανά ελλειπούσα γραμματοσειρά ανά έγγραφο προέλευσης. Εκτελείται συγχρονισμένα στο νήμα μετατροπής. Δεν ενεργοποιείται για μετατροπές εικόνας.

Για έγγραφα παρουσίασης, η αντικατάσταση γραμματοσειρών εντοπίζεται μόνο στα Windows, επειδή η μηχανή το επιλύει μέσω αντιστοίχισης γραμματοσειρών ειδικής πλατφόρμας που δεν είναι διαθέσιμη σε άλλα λειτουργικά συστήματα.

### Definition:
```python
@property
def on_font_substituted(self):
    ...
@on_font_substituted.setter
def on_font_substituted(self, value):
    ...
```

### Δείτε επίσης
* class [`ConversionEvents`](/conversion/python-net/groupdocs.conversion/conversionevents/)
