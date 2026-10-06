---
title: "on_font_substituted egenskap"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Händelsen som utlöses när ett teckensnitt som refereras av källdokumentet inte är tillgängligt och ersätts (antingen av en kundtillhandahållen FontSubstitute‑regel, av det konfigurerade standardteckensnittet, eller av …"
type: docs
url: /sv/python-net/groupdocs.conversion/conversionevents/on_font_substituted/
is_root: false
weight: 2070
---


## on_font_substituted property

Händelsen avfyras när ett teckensnitt som refereras av källdokumentet inte är tillgängligt och ersätts (antingen av en kundtillhandahållen [`FontSubstitute`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitute/) regel, av det konfigurerade standardteckensnittet, eller av konverteringspipelinens interna reserv).

Händelsen dedupliceras per `(SourceFileName, OriginalFontName)` inom ett enskilt `Converter.Convert(...)`‑anrop — prenumeranter får högst en avisering per saknat teckensnitt per källdokument. Utlöses synkront på konverteringstråden. Utlöses inte för bildkonverteringar.

För presentationsdokument upptäcks teckensnittsersättning endast på Windows, eftersom motorn löser det genom plattforms‑specifik teckensnittsmatchning som inte är tillgänglig på andra operativsystem.

### Definition:
```python
@property
def on_font_substituted(self):
    ...
@on_font_substituted.setter
def on_font_substituted(self, value):
    ...
```

### Se även
* class [`ConversionEvents`](/conversion/python-net/groupdocs.conversion/conversionevents/)
