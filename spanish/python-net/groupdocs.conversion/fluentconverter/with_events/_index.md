---
title: "método with_events"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Inicia una cadena fluida en la etapa de entrada con controladores de eventos del ciclo de vida de la conversión."
type: docs
url: /es/python-net/groupdocs.conversion/fluentconverter/with_events/
is_root: false
weight: 1070
---


## with_events {#configure}

Inicia una cadena fluida en la etapa de entrada con controladores de eventos del ciclo de vida de la conversión.

```python
def with_events(cls, configure):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| configure | `Action[ConversionEvents]` | Callable que muta la bolsa `ConversionEvents`. |

**Returns:** The source-selection stage, allowing `Load` to be chained.

### Ver también
* class [`FluentConverter`](/conversion/python-net/groupdocs.conversion/fluentconverter/)
