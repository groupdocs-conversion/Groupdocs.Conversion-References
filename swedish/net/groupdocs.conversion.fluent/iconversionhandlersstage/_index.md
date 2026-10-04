---
title: "IConversionHandlersStage"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Platt konverteringshanterare steg. Tillåter att ställa in OnConversionCompleted eller OnConversionFailed i vilken ordning som helst och hur många gånger som helst innan man går vidare till Convert / Compress. Händelser bör registreras i det tidiga steget via WithEvents./iconversionsettings/withevents istället för i detta steg."
type: docs
weight: 1480
url: /sv/net/groupdocs.conversion.fluent/iconversionhandlersstage/
---
## IConversionHandlersStage interface

Platt konverteringshanterare steg. Tillåter att ställa in `OnConversionCompleted` eller `OnConversionFailed` i vilken ordning som helst och hur många gånger som helst, innan man går vidare till `Convert` / `Compress`. Händelser bör registreras i det tidiga steget via [`WithEvents`](../iconversionsettings/withevents) istället för i detta steg.

```csharp
public interface IConversionHandlersStage : IConversionConvertOrCompress
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [OnConversionCompleted](../../groupdocs.conversion.fluent/iconversionhandlersstage/onconversioncompleted)(Action&lt;ConvertedContext&gt;) | Registrerar en återuppringning som ska anropas när en dokumentkonvertering slutförs framgångsrikt. Återanrop ersätter eventuellt tidigare inställd hanterare. |
| [OnConversionFailed](../../groupdocs.conversion.fluent/iconversionhandlersstage/onconversionfailed)(Action&lt;ConvertedContext, Exception&gt;) | Registrerar en återuppringning som ska anropas när en dokumentkonvertering misslyckas. Återanrop ersätter eventuellt tidigare inställd hanterare. |

### Se även

* interface [IConversionConvertOrCompress](../iconversionconvertorcompress)
* namespace [GroupDocs.Conversion.Fluent](../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
