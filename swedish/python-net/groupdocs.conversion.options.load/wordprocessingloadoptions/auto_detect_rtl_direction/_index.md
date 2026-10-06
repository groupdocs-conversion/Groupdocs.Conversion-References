---
title: "auto_detect_rtl_direction egenskap"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Den autodetectrtldirection egenskapen bestämmer om stycken och körningar med huvudsakligen höger-till-vänster-text har sina bidi-flaggor reparerade före konvertering."
type: docs
url: /sv/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/auto_detect_rtl_direction/
is_root: false
weight: 2010
---


## auto_detect_rtl_direction property

Egenskapen auto_detect_rtl_direction bestämmer om stycken och körningar med huvudsakligen höger‑till‑vänster‑text har sina bidi‑flaggor reparerade före konvertering.

När den är inställd på True (standard) tillämpas en heuristik som används av Microsoft Word och LibreOffice, vilket rättar rendering av arabiska/hebreiska dokument som genereras av verktyg som Google Docs och som avger OOXML utan `<w:bidi/>` och med `<w:rtl w:val="0"/>` på körningar som endast innehåller RTL-skript. Ställ in på False för att bevara den strikta OOXML-tolkningen av källmarkup.

### Definition:
```python
@property
def auto_detect_rtl_direction(self):
    ...
@auto_detect_rtl_direction.setter
def auto_detect_rtl_direction(self, value):
    ...
```

### Se även
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
