---
title: "Método get_possible_conversions"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Recupera las conversiones posibles para el documento de origen."
type: docs
url: /es/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/get_possible_conversions/
is_root: false
weight: 1080
---


## get_possible_conversions

Recupera las conversiones posibles para el documento de origen.

El objeto devuelto proporciona acceso a todas las opciones de conversión, incluidos los formatos primario y secundario, e incluye metadatos sobre el archivo de origen.

```python
def get_possible_conversions(self):
    ...
```

**Returns:** GroupDocs.Conversion.Fluent.PossibleConversions: An object containing the source description and collections of conversion formats.

### Ejemplo

```python
from groupdocs.conversion import Converter

with Converter("report.xlsx") as converter:
    conversions = converter.get_possible_conversions()
    primary = [c.format for c in conversions.all if c.is_primary]
    print(f"Primary targets for {conversions.source.description}: {primary}")
```

### Ver también
* class [`IConversionLoadOptionsOrSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/)
