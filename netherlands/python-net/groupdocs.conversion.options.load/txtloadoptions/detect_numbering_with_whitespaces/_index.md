---
title: "detect_numbering_with_whitespaces eigenschap"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "De eigenschap geeft aan hoe genummerde lijstitems worden herkend wanneer een platte‑tekstdocument wordt geconverteerd."
type: docs
url: /nl/python-net/groupdocs.conversion.options.load/txtloadoptions/detect_numbering_with_whitespaces/
is_root: false
weight: 2020
---


## detect_numbering_with_whitespaces property

De eigenschap geeft aan hoe genummerde lijstitems worden herkend wanneer een platte-tekstdocument wordt geconverteerd. De standaardwaarde is True.

Als deze optie is ingesteld op False, detecteert het lijstherkenningsalgoritme lijstparagrafen wanneer lijstnummers eindigen op een punt, rechte haak of opsommingsteken (zoals "•", "*", "-" of "o").

Als deze optie is ingesteld op True, worden spaties ook gebruikt als scheidingsteken voor lijstnummers: het lijstherkenningsalgoritme voor Arabische nummering (bijv. 1., 1.1.2.) gebruikt zowel spaties als punt (".")‑symbolen.

### Definition:
```python
@property
def detect_numbering_with_whitespaces(self):
    ...
@detect_numbering_with_whitespaces.setter
def detect_numbering_with_whitespaces(self, value):
    ...
```

### Zie ook
* class [`TxtLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/)
