---
title: "proprietà embed_full_fonts"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "La proprietà determina se il file del font completo è incorporato nel PDF anziché un sottoinsieme."
type: docs
url: /it/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/embed_full_fonts/
is_root: false
weight: 2020
---


## embed_full_fonts property

La proprietà determina se il file del font completo è incorporato nel PDF anziché un sottoinsieme.

Quando impostato su True, la dimensione del file di output aumenta ma garantisce una migliore compatibilità durante la modifica del PDF risultante. Si applica solo quando si converte da documenti WordProcessing.

### Definition:
```python
@property
def embed_full_fonts(self):
    ...
@embed_full_fonts.setter
def embed_full_fonts(self, value):
    ...
```

### Vedi anche
* class [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/)
