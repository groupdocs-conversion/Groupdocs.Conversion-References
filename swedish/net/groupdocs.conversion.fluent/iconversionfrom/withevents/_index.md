---
title: "WithEvents"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Registrera konverteringslivscykel‑händelsehanterare på en ConversionEventsgroupdocs.conversion/conversionevents‑påse som lever under konverterarens livstid och utlöses vid varje konverteringskörning. Kan anropas före eller efter WithSettingsgroupdocs.conversion.fluent/iconversionsettings/withsettings. Flera anrop ackumuleras; samma interna påse skickas till varje configure‑åtgärd så att hanterare som satts i tidigare anrop överlever om de inte skrivs över av ett senare."
type: docs
weight: 20
url: /sv/net/groupdocs.conversion.fluent/iconversionfrom/withevents/
---
## IConversionFrom.WithEvents method

Registrera konverteringslivscykel‑händelsehanterare på en [`ConversionEvents`](../../../groupdocs.conversion/conversionevents)‑påse som lever under konverterarens livstid och utlöses vid varje konverteringskörning. Kan anropas före eller efter [`WithSettings`](../../iconversionsettings/withsettings). Flera anrop ackumuleras: samma interna påse skickas till varje *configure*‑åtgärd, så att hanterare som satts i tidigare anrop överlever om de inte skrivs över av ett senare.

```csharp
public IConversionFrom WithEvents(Action<ConversionEvents> configure)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| konfigurera | Action`1 | Åtgärd som ändrar händelsepåsen. |

### Returvärde

Detta steg så att ytterligare ingångsstegsanrop eller `Load` kan kedjas.

### Se även

* class [ConversionEvents](../../../groupdocs.conversion/conversionevents)
* interface [IConversionFrom](../../iconversionfrom)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
