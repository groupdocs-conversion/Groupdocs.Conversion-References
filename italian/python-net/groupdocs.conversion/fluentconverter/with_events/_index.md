---
title: "metodo with_events"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Avvia una catena fluente nella fase di ingresso con gestori di eventi del ciclo di vita della conversione."
type: docs
url: /it/python-net/groupdocs.conversion/fluentconverter/with_events/
is_root: false
weight: 1070
---


## with_events {#configure}

Avvia una catena fluente nella fase di ingresso con gestori di eventi del ciclo di vita della conversione.

```python
def with_events(cls, configure):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| configure | `Action[ConversionEvents]` | Callable che muta il sacchetto `ConversionEvents`. |

**Returns:** The source-selection stage, allowing `Load` to be chained.

### Vedi anche
* class [`FluentConverter`](/conversion/python-net/groupdocs.conversion/fluentconverter/)
