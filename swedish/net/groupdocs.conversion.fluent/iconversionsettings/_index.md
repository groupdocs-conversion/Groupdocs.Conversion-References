---
title: "IConversionSettings"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Ställ in konverteringsinställningar eller händelser i ingångsstadiet innan Load."
type: docs
weight: 1540
url: /sv/net/groupdocs.conversion.fluent/iconversionsettings/
---
## IConversionSettings interface

Ställ in konverteringsinställningar eller händelser i inträdesstadiet (innan `Load`).

```csharp
public interface IConversionSettings
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [WithEvents](../../groupdocs.conversion.fluent/iconversionsettings/withevents)(Action&lt;ConversionEvents&gt;) | Registrera händelsehanterare för konverteringslivscykeln på en [`ConversionEvents`](../../groupdocs.conversion/conversionevents) påse som lever under konverterarens livstid och avfyras vid varje konverteringskörning. Den sitter i samma ingångsstadium som [`WithSettings`](./withsettings). Flera anrop ackumuleras: samma interna påse skickas till varje *configure* åtgärd, så hanterare som ställts in i tidigare anrop överlever om de inte skrivs över av ett senare. |
| [WithSettings](../../groupdocs.conversion.fluent/iconversionsettings/withsettings)(Func&lt;ConverterSettings&gt;) | Ställ in konverteringsinställningar |

### Se även

* namespace [GroupDocs.Conversion.Fluent](../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
