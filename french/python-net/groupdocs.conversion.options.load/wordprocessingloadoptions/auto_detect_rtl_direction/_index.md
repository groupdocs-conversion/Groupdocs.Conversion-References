---
title: "propriété auto_detect_rtl_direction"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "La propriété autodetectrtldirection détermine si les paragraphes et les segments contenant principalement du texte de droite à gauche ont leurs indicateurs bidi réparés avant la conversion."
type: docs
url: /fr/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/auto_detect_rtl_direction/
is_root: false
weight: 2010
---


## auto_detect_rtl_direction property

La propriété auto_detect_rtl_direction détermine si les paragraphes et les runs contenant principalement du texte de droite à gauche ont leurs indicateurs bidi réparés avant la conversion.

Lorsqu'elle est définie sur True (par défaut), la propriété applique une heuristique utilisée par Microsoft Word et LibreOffice, corrigeant le rendu des documents arabes/hébreux générés par des outils tels que Google Docs qui émettent du OOXML sans `<w:bidi/>` et avec `<w:rtl w:val="0"/>` sur les segments contenant uniquement du script RTL. Définissez-la sur False pour préserver l'interprétation stricte du OOXML du balisage source.

### Definition:
```python
@property
def auto_detect_rtl_direction(self):
    ...
@auto_detect_rtl_direction.setter
def auto_detect_rtl_direction(self, value):
    ...
```

### Voir aussi
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
