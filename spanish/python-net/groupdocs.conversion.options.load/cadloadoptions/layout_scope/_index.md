---
title: "propiedad layout_scope"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "El alcance de diseño que determina qué espacios de dibujo se convierten."
type: docs
url: /es/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_scope/
is_root: false
weight: 2070
---


## layout_scope property

El alcance de diseño que determina qué espacios de dibujo se convierten. Por defecto es [`CadLayoutScope.both`](/conversion/python-net/groupdocs.conversion.options.load/cadlayoutscope/), lo que no restringe la conversión. Se ignora cuando se proporciona [`CadLoadOptions.layout_names`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/), porque los nombres de diseño explícitos siempre prevalecen. Un valor `None` se trata como [`CadLayoutScope.both`](/conversion/python-net/groupdocs.conversion.options.load/cadlayoutscope/).

Si el alcance no selecciona ninguna de las hojas ofrecidas por un dibujo, la conversión falla con `InvalidLoadOptionsException`, que indica el alcance y las hojas disponibles en lugar de renderizar los espacios excluidos. Un dibujo que no ofrece ninguna hoja no se ve afectado y aún se convierte como una única unidad. No se respeta al convertir a PDF/UA-1, por la razón indicada en [`CadLoadOptions.layout_names`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/).

### Definition:
```python
@property
def layout_scope(self):
    ...
@layout_scope.setter
def layout_scope(self, value):
    ...
```

### Ver también
* class [`CadLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/)
