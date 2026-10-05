---
title: "auto_detect_rtl_direction Eigenschaft"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Die autodetectrtldirection Eigenschaft bestimmt, ob Absätze und Läufe mit überwiegend rechts-nach-links Text ihre Bidi-Flags vor der Konvertierung repariert werden."
type: docs
url: /de/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/auto_detect_rtl_direction/
is_root: false
weight: 2010
---


## auto_detect_rtl_direction property

Die auto_detect_rtl_direction-Eigenschaft bestimmt, ob Absätze und Läufe mit überwiegend rechts-nach-links‑Text ihre Bidi‑Flags vor der Konvertierung repariert werden.

Wenn sie auf True (Standard) gesetzt ist, wendet die Eigenschaft eine von Microsoft Word und LibreOffice verwendete Heuristik an, die Darstellung von Arabisch/Hebräisch-Dokumenten korrigiert, die von Werkzeugen wie Google Docs erzeugt werden und OOXML ohne `<w:bidi/>` und mit `<w:rtl w:val="0"/>` in Läufen enthalten, die nur RTL‑Skript enthalten. Setze sie auf False, um die strenge OOXML‑Interpretation des Quell‑Markups beizubehalten.

### Definition:
```python
@property
def auto_detect_rtl_direction(self):
    ...
@auto_detect_rtl_direction.setter
def auto_detect_rtl_direction(self, value):
    ...
```

### Siehe auch
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
