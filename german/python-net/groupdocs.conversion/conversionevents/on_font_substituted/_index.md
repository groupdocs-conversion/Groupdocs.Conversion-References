---
title: "on_font_substituted Eigenschaft"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Das Ereignis wird ausgelöst, wenn eine im Quelldokument referenzierte Schriftart nicht verfügbar ist und ersetzt wird (entweder durch eine vom Kunden bereitgestellte FontSubstitute‑Regel, durch die konfigurierte Standardschriftart oder durch das…"
type: docs
url: /de/python-net/groupdocs.conversion/conversionevents/on_font_substituted/
is_root: false
weight: 2070
---


## on_font_substituted property

Das Ereignis wird ausgelöst, wenn eine im Quell‑Dokument referenzierte Schriftart nicht verfügbar ist und ersetzt wird (entweder durch eine vom Kunden bereitgestellte [`FontSubstitute`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitute/) Regel, durch die konfigurierte Standardschriftart oder durch den internen Fallback der Konvertierungspipeline).

Das Ereignis wird pro `(SourceFileName, OriginalFontName)` innerhalb eines einzelnen `Converter.Convert(...)` Aufrufs dedupliziert — Abonnenten erhalten höchstens eine Benachrichtigung pro fehlender Schriftart pro Quelldokument. Es wird synchron im Konvertierungsthread ausgelöst. Nicht ausgelöst bei Bildkonvertierungen.

Für Präsentationsdokumente wird die Schriftart‑Substitution nur unter Windows erkannt, da die Engine sie über plattformspezifisches Schriftarten‑Matching auflöst, das auf anderen Betriebssystemen nicht verfügbar ist.

### Definition:
```python
@property
def on_font_substituted(self):
    ...
@on_font_substituted.setter
def on_font_substituted(self, value):
    ...
```

### Siehe auch
* class [`ConversionEvents`](/conversion/python-net/groupdocs.conversion/conversionevents/)
