---
title: "ιδιότητα auto_detect_rtl_direction"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Η ιδιότητα autodetectrtldirection καθορίζει εάν οι παράγραφοι και τα τμήματα κειμένου με κυρίως δεξιά‑προς‑αριστερό κείμενο έχουν τις σημαίες bidi διορθωμένες πριν από τη μετατροπή."
type: docs
url: /el/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/auto_detect_rtl_direction/
is_root: false
weight: 2010
---


## auto_detect_rtl_direction property

Η ιδιότητα auto_detect_rtl_direction καθορίζει εάν οι παράγραφοι και τα τμήματα κειμένου με κυρίως δεξιόστροφη (right-to-left) γραφή έχουν τις σημαίες bidi διορθωμένες πριν από τη μετατροπή.

Όταν ορίζεται σε True (προεπιλογή), η ιδιότητα εφαρμόζει μια ευρετική μέθοδο που χρησιμοποιούν το Microsoft Word και το LibreOffice, διορθώνοντας την απόδοση εγγράφων Αραβικών/Εβραϊκών που δημιουργούνται από εργαλεία όπως το Google Docs και εκδίδουν OOXML χωρίς `<w:bidi/>` και με `<w:rtl w:val=\"0\"/>` σε τμήματα που περιέχουν μόνο δεξιά‑προς‑αριστερό κείμενο. Ορίστε σε False για να διατηρήσετε την αυστηρή ερμηνεία OOXML της πηγαίας σήμανσης.

### Definition:
```python
@property
def auto_detect_rtl_direction(self):
    ...
@auto_detect_rtl_direction.setter
def auto_detect_rtl_direction(self, value):
    ...
```

### Δείτε επίσης
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
