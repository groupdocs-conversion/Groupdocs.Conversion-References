---
title: "método with_events"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Registra controladores de eventos del ciclo de vida de la conversión en una bolsa ConversionEvents que vive durante la vida útil del conversor y se dispara en cada ejecución de conversión."
type: docs
url: /es/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/
is_root: false
weight: 1010
---


## with_events {#configure}

Registra controladores de eventos del ciclo de vida de la conversión en una bolsa [`ConversionEvents`](/conversion/python-net/groupdocs.conversion/conversionevents/) que vive durante la vida útil del convertidor y se dispara en cada ejecución de conversión.

Se encuentra en la misma etapa de entrada que [`IConversionSettings.with_settings`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_settings/). Las llamadas múltiples se acumulan: la misma bolsa interna se pasa a cada acción `configure`, por lo que los manejadores establecidos en llamadas anteriores permanecen a menos que sean sobrescritos por una posterior.

```python
def with_events(self, configure):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| configure | `Action[ConversionEvents]` | Acción que muta la bolsa de eventos. |

**Returns:** The source-selection stage so that `Load` may be chained.

### Ver también
* class [`IConversionSettings`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/)
