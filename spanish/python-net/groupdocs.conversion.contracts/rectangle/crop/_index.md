---
title: "crop método"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Crea una versión recortada del rectangle actual eliminando los márgenes especificados."
type: docs
url: /es/python-net/groupdocs.conversion.contracts/rectangle/crop/
is_root: false
weight: 1010
---


## crop {#crop_left-crop_top-crop_right-crop_bottom}

Crea una versión recortada del rectangle actual eliminando los márgenes especificados.

```python
def crop(self, crop_left, crop_top, crop_right, crop_bottom):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| crop_left | `int` | El número de píxeles a eliminar del lado izquierdo. |
| crop_top | `int` | El número de píxeles a eliminar del lado superior. |
| crop_right | `int` | El número de píxeles a eliminar del lado derecho. |
| crop_bottom | `int` | El número de píxeles a eliminar del lado inferior. |

**Returns:** Rectangle: A new cropped rectangle.

### Ver también
* class [`Rectangle`](/conversion/python-net/groupdocs.conversion.contracts/rectangle/)
