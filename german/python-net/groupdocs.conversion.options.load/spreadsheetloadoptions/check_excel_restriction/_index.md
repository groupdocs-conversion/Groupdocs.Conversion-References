---
title: "check_excel_restriction Eigenschaft"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Die Eigenschaft bestimmt, ob Excel‑Dateibeschränkungen beim Ändern von zellbezogenen Objekten geprüft werden."
type: docs
url: /de/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/check_excel_restriction/
is_root: false
weight: 2030
---


## check_excel_restriction property

Die Eigenschaft bestimmt, ob Excel‑Dateibeschränkungen beim Ändern von zellbezogenen Objekten geprüft werden.

Wenn true, führt der Versuch, eine Zeichenkette länger als 32 K einzugeben, zu einer Ausnahme. Wenn false, wird die Eingabezeichenkette akzeptiert, sodass der vollständige Wert in andere Formate wie CSV ausgegeben werden kann. Das Speichern der Arbeitsmappe zurück im Excel‑Format mit solchen ungültigen Werten kann jedoch unerwartete Fehler verursachen.

### Definition:
```python
@property
def check_excel_restriction(self):
    ...
@check_excel_restriction.setter
def check_excel_restriction(self, value):
    ...
```

### Siehe auch
* class [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)
