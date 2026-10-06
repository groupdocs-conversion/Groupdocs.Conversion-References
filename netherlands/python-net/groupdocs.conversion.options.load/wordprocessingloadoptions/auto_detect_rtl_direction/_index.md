---
title: "auto_detect_rtl_direction eigenschap"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "De autodetectrtldirection eigenschap bepaalt of alinea's en runs met overwegend rechts-naar-links tekst hun bidi‑vlaggen laten repareren vóór conversie."
type: docs
url: /nl/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/auto_detect_rtl_direction/
is_root: false
weight: 2010
---


## auto_detect_rtl_direction property

De auto_detect_rtl_direction eigenschap bepaalt of alinea's en runs met overwegend rechts-naar-links tekst hun bidi‑vlaggen vóór conversie worden gerepareerd.

Wanneer ingesteld op True (standaard), past de eigenschap een heuristiek toe die wordt gebruikt door Microsoft Word en LibreOffice, waardoor de weergave van Arabische/Hebreeuwse documenten die zijn gegenereerd door tools zoals Google Docs en OOXML zonder `<w:bidi/>` en met `<w:rtl w:val="0"/>` op runs die alleen RTL‑script bevatten, wordt gecorrigeerd. Stel in op False om de strikte OOXML‑interpretatie van de bron‑opmaak te behouden.

### Definition:
```python
@property
def auto_detect_rtl_direction(self):
    ...
@auto_detect_rtl_direction.setter
def auto_detect_rtl_direction(self, value):
    ...
```

### Zie ook
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
