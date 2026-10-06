---
title: "with_events‑metod"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Registrerar händelsehanterare för konverteringslivscykeln i en ConversionEvents‑påse som lever under konverterarens livstid och utlöses vid varje konverteringskörning."
type: docs
url: /sv/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/
is_root: false
weight: 1010
---


## with_events {#configure}

Registrerar konverteringslivscykel‑händelsehanterare på en [`ConversionEvents`](/conversion/python-net/groupdocs.conversion/conversionevents/) påse som lever under konverterarens livstid och avfyras vid varje konverteringskörning.

Sitter på samma ingångssteg som [`IConversionSettings.with_settings`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_settings/). Flera anrop ackumuleras: samma interna påse skickas till varje `configure`‑åtgärd, så handlare som satts i tidigare anrop överlever om de inte skrivs över av ett senare.

```python
def with_events(self, configure):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| configure | `Action[ConversionEvents]` | Åtgärd som ändrar händelsepåsen. |

**Returns:** The source-selection stage so that `Load` may be chained.

### Se även
* class [`IConversionSettings`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/)
