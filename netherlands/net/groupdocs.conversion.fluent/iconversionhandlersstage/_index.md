---
title: "IConversionHandlersStage"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Vlakke conversiehandlersfase. Staat toe OnConversionCompleted of OnConversionFailed in willekeurige volgorde en elk aantal keren in te stellen voordat wordt overgegaan tot Convert / Compress. Gebeurtenissen moeten in een vroeg stadium worden geregistreerd via WithEvents./iconversionsettings/withevents in plaats van in deze fase."
type: docs
weight: 1480
url: /nl/net/groupdocs.conversion.fluent/iconversionhandlersstage/
---
## IConversionHandlersStage interface

Vlakke conversiehandlersfase. Staat toe `OnConversionCompleted` of `OnConversionFailed` in willekeurige volgorde en elk aantal keren in te stellen, voordat wordt overgegaan tot `Convert` / `Compress`. Gebeurtenissen moeten in een vroeg stadium worden geregistreerd via [`WithEvents`](../iconversionsettings/withevents) in plaats van in deze fase.

```csharp
public interface IConversionHandlersStage : IConversionConvertOrCompress
```

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [OnConversionCompleted](../../groupdocs.conversion.fluent/iconversionhandlersstage/onconversioncompleted)(Action&lt;ConvertedContext&gt;) | Registreert een callback die wordt aangeroepen wanneer een documentconversie succesvol wordt voltooid. Opnieuw aanroepen vervangt elke eerder ingestelde handler. |
| [OnConversionFailed](../../groupdocs.conversion.fluent/iconversionhandlersstage/onconversionfailed)(Action&lt;ConvertedContext, Exception&gt;) | Registreert een callback die wordt aangeroepen wanneer een documentconversie mislukt. Opnieuw aanroepen vervangt elke eerder ingestelde handler. |

### Zie ook

* interface [IConversionConvertOrCompress](../iconversionconvertorcompress)
* namespace [GroupDocs.Conversion.Fluent](../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
