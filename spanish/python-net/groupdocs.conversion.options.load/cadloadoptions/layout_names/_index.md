---
title: "propiedad layout_names"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Los nombres de diseño a convertir."
type: docs
url: /es/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/
is_root: false
weight: 2060
---


## layout_names property

Los nombres de diseño a convertir.

No se respeta al convertir a PDF/UA-1. Ese objetivo renderiza el dibujo como una única página etiquetada, que no puede contener una hoja por cada diseño seleccionado, por lo que se convierte todo el dibujo en su lugar y nada de lo aquí descrito se aplica.

Todos los demás destinos, incluido PDF, respetan la selección. En esos destinos, los nombres se comparan exactamente con los diseños que lleva el dibujo, de modo que un nombre que difiere solo en mayúsculas/minúsculas se considera un nombre diferente. Un nombre que no coincide con nada se descarta y solo le cuesta al llamador esa hoja; una lista en la que nada coincide hace que la conversión falle con una `InvalidLoadOptionsException` que nombra los nombres que no se encontraron y los diseños que el dibujo sí lleva, en lugar de renderizar hojas que el llamador no solicitó. Un dibujo que no lleva ningún diseño está exento: no hay nada para que un nombre coincida, por lo que ninguno es rechazado.

### Definition:
```python
@property
def layout_names(self):
    ...
@layout_names.setter
def layout_names(self, value):
    ...
```

### Ver también
* class [`CadLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/)
