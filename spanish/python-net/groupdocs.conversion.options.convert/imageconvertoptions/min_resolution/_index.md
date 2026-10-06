---
title: "propiedad min_resolution"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "El límite inferior por eje aplicado al DPI de renderizado limitado cuando ImageConvertOptions.CapResolutionToPageContent está habilitado."
type: docs
url: /es/python-net/groupdocs.conversion.options.convert/imageconvertoptions/min_resolution/
is_root: false
weight: 2130
---


## min_resolution property

El límite inferior por eje aplicado al DPI de renderizado limitado cuando [`ImageConvertOptions.CapResolutionToPageContent`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/cap_resolution_to_page_content/) está habilitado.

El DPI limitado nunca se reduce por debajo de este valor. El valor predeterminado es 0 (sin límite inferior).

### Definition:
```python
@property
def min_resolution(self):
    ...
@min_resolution.setter
def min_resolution(self, value):
    ...
```

### Ver también
* class [`ImageConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/)
