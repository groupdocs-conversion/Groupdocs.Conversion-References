---
title: "método with_events"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Registre controladores de eventos del ciclo de vida de la conversión en una bolsa ConversionEvents que vive durante la vida útil del convertidor y se dispara en cada ejecución de conversión."
type: docs
url: /es/python-net/groupdocs.conversion.fluent/iconversionfrom/with_events/
is_root: false
weight: 1070
---


## with_events {#configure}

Registra controladores de eventos del ciclo de vida de la conversión en una bolsa [`ConversionEvents`](/conversion/python-net/groupdocs.conversion/conversionevents/) que vive durante la vida útil del convertidor y se dispara en cada ejecución de conversión.

Puede llamarse antes o después de [`IConversionSettings.with_settings`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_settings/).
Las llamadas múltiples se acumulan: la misma bolsa interna se pasa a cada acción `configure`, por lo que los controladores establecidos en llamadas anteriores sobreviven a menos que sean sobrescritos por una posterior.

```python
def with_events(self, configure):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| configure | `Action[ConversionEvents]` | Acción que muta la bolsa de eventos. |

**Returns:** This stage so that further entry-stage calls or `Load` may be chained.

### Ver también
* class [`IConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionfrom/)
