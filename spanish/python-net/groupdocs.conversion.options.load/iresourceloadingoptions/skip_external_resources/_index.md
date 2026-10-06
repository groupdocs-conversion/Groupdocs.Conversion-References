---
title: "propiedad skip_external_resources"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "La propiedad indica si los recursos externos están cargados."
type: docs
url: /es/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/skip_external_resources/
is_root: false
weight: 2010
---


## skip_external_resources property

La propiedad indica si los recursos externos están cargados.

Si es True, no se cargarán todos los recursos externos excepto los que están en la lista [`IResourceLoadingOptions.whitelisted_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/whitelisted_resources/). Predeterminado: True.

### Definition:
```python
@property
def skip_external_resources(self):
    ...
@skip_external_resources.setter
def skip_external_resources(self, value):
    ...
```

### Ver también
* class [`IResourceLoadingOptions`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/)
