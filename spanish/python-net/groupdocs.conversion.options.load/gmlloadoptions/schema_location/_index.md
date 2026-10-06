---
title: "propiedad schema_location"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "La schemalocation es una lista separada por espacios de pares de URI, donde el primer URI de cada par es el URI del espacio de nombres y el segundo URI es la ruta al esquema XML de ese espacio de nombres."
type: docs
url: /es/python-net/groupdocs.conversion.options.load/gmlloadoptions/schema_location/
is_root: false
weight: 2040
---


## schema_location property

El schema_location es una lista separada por espacios de pares de URI, donde el primer URI de cada par es el URI del espacio de nombres y el segundo URI es la ruta al esquema XML de ese espacio de nombres.

Si se establece en None, Conversion intentará leer el atributo schemaLocation del elemento raíz del documento. El valor predeterminado es None.

### Definition:
```python
@property
def schema_location(self):
    ...
@schema_location.setter
def schema_location(self, value):
    ...
```

### Ver también
* class [`GmlLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/gmlloadoptions/)
