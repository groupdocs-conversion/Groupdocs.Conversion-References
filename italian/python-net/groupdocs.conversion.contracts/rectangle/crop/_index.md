---
title: "crop metodo"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Crea una versione ritagliata del rettangolo corrente rimuovendo i margini specificati."
type: docs
url: /it/python-net/groupdocs.conversion.contracts/rectangle/crop/
is_root: false
weight: 1010
---


## crop {#crop_left-crop_top-crop_right-crop_bottom}

Crea una versione ritagliata del rettangolo corrente rimuovendo i margini specificati.

```python
def crop(self, crop_left, crop_top, crop_right, crop_bottom):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| crop_left | `int` | Il numero di pixel da rimuovere dal lato sinistro. |
| crop_top | `int` | Il numero di pixel da rimuovere dal lato superiore. |
| crop_right | `int` | Il numero di pixel da rimuovere dal lato destro. |
| crop_bottom | `int` | Il numero di pixel da rimuovere dal lato inferiore. |

**Returns:** Rectangle: A new cropped rectangle.

### Vedi anche
* class [`Rectangle`](/conversion/python-net/groupdocs.conversion.contracts/rectangle/)
