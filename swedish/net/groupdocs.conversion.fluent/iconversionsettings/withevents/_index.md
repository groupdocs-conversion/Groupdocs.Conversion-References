---
title: "WithEvents"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Registrera händelsehanterare för konverteringslivscykeln på en ConversionEventsgroupdocs.conversion/conversionevents‑påse som lever under konverterarens livstid och utlöses vid varje konverteringskörning. Den sitter i samma inledningssteg som WithSettingsgroupdocs.conversion.fluent/iconversionsettings/withsettings. Flera anrop ackumulerar; samma interna påse skickas till varje configure action så att hanterare som satts i tidigare anrop överlever om de inte skrivs över av ett senare."
type: docs
weight: 10
url: /sv/net/groupdocs.conversion.fluent/iconversionsettings/withevents/
---
## IConversionSettings.WithEvents method

Registrera händelsehanterare för konverteringslivscykeln på en [`ConversionEvents`](../../../groupdocs.conversion/conversionevents)‑påse som lever under konverterarens livstid och utlöses vid varje konverteringskörning. Den sitter i samma inledningssteg som [`WithSettings`](../withsettings). Flera anrop ackumulerar: samma interna påse skickas till varje *configure*‑åtgärd, så att hanterare som satts i tidigare anrop överlever om de inte skrivs över av ett senare.

```csharp
public IConversionFrom WithEvents(Action<ConversionEvents> configure)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| konfigurera | Action`1 | Åtgärd som ändrar händelsepåsen. |

### Returvärde

Källvalsstadiet så att `Load` kan kedjas.

### Se även

* interface [IConversionFrom](../../iconversionfrom)
* class [ConversionEvents](../../../groupdocs.conversion/conversionevents)
* interface [IConversionSettings](../../iconversionsettings)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
