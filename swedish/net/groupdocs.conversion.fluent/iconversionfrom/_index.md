---
title: "IConversionFrom"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Ställ in källa för konvertering"
type: docs
weight: 1440
url: /sv/net/groupdocs.conversion.fluent/iconversionfrom/
---
## IConversionFrom interface

Ställ in källa för konvertering

```csharp
public interface IConversionFrom
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Load](../../groupdocs.conversion.fluent/iconversionfrom/load#load_1)(Func&lt;Stream&gt;) | Ange källdokumentström |
| [Load](../../groupdocs.conversion.fluent/iconversionfrom/load#load)(Func&lt;Stream[]&gt;) | Ange array med strömmar för källdokument |
| [Load](../../groupdocs.conversion.fluent/iconversionfrom/load#load_2)(string) | Ange filnamn för källdokument |
| [Load](../../groupdocs.conversion.fluent/iconversionfrom/load#load_3)(string[]) | Ange array med källdokument |
| [WithEvents](../../groupdocs.conversion.fluent/iconversionfrom/withevents)(Action&lt;ConversionEvents&gt;) | Registrera händelsehanterare för konverteringslivscykeln på en [`ConversionEvents`](../../groupdocs.conversion/conversionevents) påse som lever under konverterarens livstid och utlöses vid varje konverteringskörning. Kan anropas före eller efter [`WithSettings`](../iconversionsettings/withsettings). Flera anrop ackumuleras: samma interna påse skickas till varje *configure* åtgärd, så hanterare som satts i tidigare anrop överlever om de inte skrivs över av ett senare. |

### Se även

* namespace [GroupDocs.Conversion.Fluent](../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
