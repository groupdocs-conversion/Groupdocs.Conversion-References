---
title: "detect_numbering_with_whitespaces-Eigenschaft"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Die Eigenschaft gibt an, wie nummerierte Listenelemente erkannt werden, wenn ein Klartextdokument konvertiert wird."
type: docs
url: /de/python-net/groupdocs.conversion.options.load/txtloadoptions/detect_numbering_with_whitespaces/
is_root: false
weight: 2020
---


## detect_numbering_with_whitespaces property

Die Eigenschaft legt fest, wie nummerierte Listenelemente erkannt werden, wenn ein Klartextdokument konvertiert wird. Der Standardwert ist `True`.

Wenn diese Option auf False gesetzt ist, erkennt der Listenerkennungsalgorithmus Listabsätze, wenn Listennummern entweder mit einem Punkt, einer rechten Klammer oder Aufzählungszeichen (wie "•", "*", "-" oder "o") enden.

Wenn diese Option auf True gesetzt ist, werden Leerzeichen ebenfalls als Trennzeichen für Listennummern verwendet: Der Listenerkennungsalgorithmus für arabisch‑stilierte Nummerierung (z. B. 1., 1.1.2.) nutzt sowohl Leerzeichen als auch Punkt‑Symbole (".").

### Definition:
```python
@property
def detect_numbering_with_whitespaces(self):
    ...
@detect_numbering_with_whitespaces.setter
def detect_numbering_with_whitespaces(self, value):
    ...
```

### Siehe auch
* class [`TxtLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/)
