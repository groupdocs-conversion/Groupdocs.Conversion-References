---
title: "on_font_substituted eigenschap"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Het evenement dat wordt geactiveerd wanneer een lettertype dat door het bron‑document wordt gerefereerd niet beschikbaar is en wordt vervangen (ofwel door een door de klant geleverde FontSubstitute‑regel, door het geconfigureerde standaardlettertype, of door de…"
type: docs
url: /nl/python-net/groupdocs.conversion/conversionevents/on_font_substituted/
is_root: false
weight: 2070
---


## on_font_substituted property

Het evenement wordt geactiveerd wanneer een lettertype dat door het brondocument wordt gerefereerd niet beschikbaar is en wordt vervangen (ofwel door een door de klant geleverde [`FontSubstitute`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitute/) regel, door het geconfigureerde standaardlettertype, of door de interne fallback van de conversiepijplijn).

Het evenement wordt gededupliceerd per `(SourceFileName, OriginalFontName)` binnen één `Converter.Convert(...)`‑aanroep — abonnees ontvangen maximaal één melding per ontbrekend lettertype per bron‑document. Wordt synchroon geactiveerd op de conversiedraad. Niet gegenereerd voor afbeelding‑conversies.

Voor presentatiedocumenten wordt lettertype‑substitutie alleen op Windows gedetecteerd, omdat de engine dit oplost via platformspecifieke lettertype‑matching die niet beschikbaar is op andere besturingssystemen.

### Definition:
```python
@property
def on_font_substituted(self):
    ...
@on_font_substituted.setter
def on_font_substituted(self, value):
    ...
```

### Zie ook
* class [`ConversionEvents`](/conversion/python-net/groupdocs.conversion/conversionevents/)
