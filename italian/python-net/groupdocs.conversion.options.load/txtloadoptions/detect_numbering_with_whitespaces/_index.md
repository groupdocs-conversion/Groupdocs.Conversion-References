---
title: "proprietà detect_numbering_with_whitespaces"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "La proprietà specifica come vengono riconosciuti gli elementi di elenco numerato quando un documento di testo semplice viene convertito."
type: docs
url: /it/python-net/groupdocs.conversion.options.load/txtloadoptions/detect_numbering_with_whitespaces/
is_root: false
weight: 2020
---


## detect_numbering_with_whitespaces property

La proprietà specifica come gli elementi di elenco numerato vengono riconosciuti quando un documento di testo semplice viene convertito. Il valore predefinito è True.

Se questa opzione è impostata su False, l'algoritmo di riconoscimento degli elenchi rileva i paragrafi di elenco quando i numeri degli elenchi terminano con un punto, una parentesi chiusa o simboli di elenco puntato (come "•", "*", "-" o "o").

Se questa opzione è impostata su True, gli spazi bianchi sono anche usati come delimitatori dei numeri di elenco: l'algoritmo di riconoscimento degli elenchi per la numerazione in stile arabo (ad es., 1., 1.1.2.) utilizza sia gli spazi bianchi sia il punto (".") come simboli.

### Definition:
```python
@property
def detect_numbering_with_whitespaces(self):
    ...
@detect_numbering_with_whitespaces.setter
def detect_numbering_with_whitespaces(self, value):
    ...
```

### Vedi anche
* class [`TxtLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/)
