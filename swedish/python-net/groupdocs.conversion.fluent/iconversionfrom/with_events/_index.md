---
title: "with_events‑metod"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Registrera konverteringslivscykel‑händelsehanterare i en ConversionEvents‑påse som lever under konverterarens livstid och utlöses vid varje konverteringskörning."
type: docs
url: /sv/python-net/groupdocs.conversion.fluent/iconversionfrom/with_events/
is_root: false
weight: 1070
---


## with_events {#configure}

Registrera konverteringslivscykelns händelsehanterare på en [`ConversionEvents`](/conversion/python-net/groupdocs.conversion/conversionevents/) påse som lever under konverterarens livstid och utlöses vid varje konverteringskörning.

Kan anropas före eller efter [`IConversionSettings.with_settings`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_settings/).
Flera anrop ackumuleras: samma interna påse skickas till varje `configure`-åtgärd, så hanterare som ställts in i tidigare anrop överlever om de inte skrivs över av ett senare.

```python
def with_events(self, configure):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| configure | `Action[ConversionEvents]` | Åtgärd som ändrar händelsepåsen. |

**Returns:** This stage so that further entry-stage calls or `Load` may be chained.

### Se även
* class [`IConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionfrom/)
