---
title: "proprietà on_font_substituted"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "L'evento generato quando un carattere referenziato dal documento sorgente non è disponibile e viene sostituito (sia da una regola FontSubstitute fornita dal cliente, sia dal carattere predefinito configurato, o da…"
type: docs
url: /it/python-net/groupdocs.conversion/conversionevents/on_font_substituted/
is_root: false
weight: 2070
---


## on_font_substituted property

L'evento viene generato quando un carattere (font) referenziato dal documento sorgente non è disponibile e viene sostituito (sia tramite una regola [`FontSubstitute`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitute/) fornita dal cliente, dal carattere predefinito configurato, o dal fallback interno della pipeline di conversione).

L'evento è deduplicato per `(SourceFileName, OriginalFontName)` all'interno di una singola chiamata `Converter.Convert(...)` — gli iscritti ricevono al massimo una notifica per carattere mancante per documento sorgente. Viene attivato in modo sincrono sul thread di conversione. Non viene sollevato per conversioni di immagini.

Per i documenti di presentazione, la sostituzione dei caratteri viene rilevata solo su Windows, perché il motore la risolve tramite il matching dei caratteri specifico della piattaforma, non disponibile su altri sistemi operativi.

### Definition:
```python
@property
def on_font_substituted(self):
    ...
@on_font_substituted.setter
def on_font_substituted(self, value):
    ...
```

### Vedi anche
* class [`ConversionEvents`](/conversion/python-net/groupdocs.conversion/conversionevents/)
