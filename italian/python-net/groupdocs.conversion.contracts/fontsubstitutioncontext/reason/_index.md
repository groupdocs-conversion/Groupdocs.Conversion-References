---
title: "proprietà reason"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Il messaggio di sostituzione esattamente come riportato dalla pipeline di conversione, verbatim e non analizzato."
type: docs
url: /it/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/reason/
is_root: false
weight: 2020
---


## reason property

Il messaggio di sostituzione esattamente come riportato dalla pipeline di conversione, verbatim e non analizzato.

Per i documenti che espongono i nomi dei font in modo strutturato, questo può essere None (usa [`FontSubstitutionContext.original_font_name`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/original_font_name/) / [`FontSubstitutionContext.substitute_font_name`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/substitute_font_name/)); per gli altri contiene la descrizione completa leggibile dall'uomo, che indica sia il font mancante sia il font sostitutivo.

### Definition:
```python
@property
def reason(self):
    ...
```

### Vedi anche
* class [`FontSubstitutionContext`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/)
