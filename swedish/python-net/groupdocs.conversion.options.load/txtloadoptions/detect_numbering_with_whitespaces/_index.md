---
title: "detect_numbering_with_whitespaces egenskap"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Egenskapen anger hur numrerade listobjekt identifieras när ett rentextdokument konverteras."
type: docs
url: /sv/python-net/groupdocs.conversion.options.load/txtloadoptions/detect_numbering_with_whitespaces/
is_root: false
weight: 2020
---


## detect_numbering_with_whitespaces property

Egenskapen anger hur numrerade listobjekt identifieras när ett rent textdokument konverteras. Standardvärdet är True.

Om detta alternativ är satt till False, upptäcker listigenkänningsalgoritmen listparagrafer när listnummer avslutas med antingen en punkt, en högra parentes eller punkttecken (såsom "•", "*", "-" eller "o").

Om detta alternativ är satt till True, används mellanslag även som avgränsare för listnummer: listigenkänningsalgoritmen för arabiskt‑stilnumrering (t.ex. 1., 1.1.2.) använder både mellanslag och punkt (".")‑symboler.

### Definition:
```python
@property
def detect_numbering_with_whitespaces(self):
    ...
@detect_numbering_with_whitespaces.setter
def detect_numbering_with_whitespaces(self, value):
    ...
```

### Se även
* class [`TxtLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/)
