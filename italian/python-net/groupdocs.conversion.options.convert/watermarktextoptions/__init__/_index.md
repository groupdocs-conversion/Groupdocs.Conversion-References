---
title: "costruttore __init__"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Inizializza un'istanza di WatermarkTextOptions con il testo della filigrana specificato."
type: docs
url: /it/python-net/groupdocs.conversion.options.convert/watermarktextoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#text}

Inizializza un'istanza di WatermarkTextOptions con il testo della filigrana specificato.

```python
def __init__(self, text):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| text | `str` | Il testo da utilizzare come watermark. |

### Esempio

```python
from groupdocs.conversion.options.convert import WatermarkTextOptions

# Crea un watermark con il testo "DRAFT"
watermark = WatermarkTextOptions("DRAFT")
```

### Vedi anche
* class [`WatermarkTextOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarktextoptions/)
