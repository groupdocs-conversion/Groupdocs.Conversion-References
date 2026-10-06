---
title: "proprietà min_resolution"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Il limite inferiore per asse applicato al DPI di rendering limitato quando ImageConvertOptions.CapResolutionToPageContent è abilitato."
type: docs
url: /it/python-net/groupdocs.conversion.options.convert/imageconvertoptions/min_resolution/
is_root: false
weight: 2130
---


## min_resolution property

Il limite inferiore per asse applicato al DPI di rendering limitato quando [`ImageConvertOptions.CapResolutionToPageContent`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/cap_resolution_to_page_content/) è abilitato.

Il DPI limitato non viene mai ridotto al di sotto di questo valore. Il valore predefinito è 0 (nessun limite inferiore).

### Definition:
```python
@property
def min_resolution(self):
    ...
@min_resolution.setter
def min_resolution(self, value):
    ...
```

### Vedi anche
* class [`ImageConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/)
