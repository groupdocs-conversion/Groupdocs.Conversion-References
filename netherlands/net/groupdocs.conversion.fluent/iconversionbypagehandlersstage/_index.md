---
title: "IConversionByPageHandlersStage"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Vlakgemaakte bypage-conversie‑handlers‑fase. Perpage spiegel van IConversionHandlersStage./iconversionhandlersstage."
type: docs
weight: 1320
url: /nl/net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/
---
## IConversionByPageHandlersStage interface

Vlakgemaakte by‑page-conversie‑handlers‑fase. Per‑page spiegel van [`IConversionHandlersStage`](../iconversionhandlersstage).

```csharp
public interface IConversionByPageHandlersStage : IConversionConvertOrCompress
```

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [OnConversionCompleted](../../groupdocs.conversion.fluent/iconversionbypagehandlersstage/onconversioncompleted)(Action&lt;ConvertedPageContext&gt;) | Registreert een callback die wordt aangeroepen wanneer een paginaconversie succesvol wordt voltooid. Opnieuw aanroepen vervangt elke eerder ingestelde handler. |
| [OnConversionFailed](../../groupdocs.conversion.fluent/iconversionbypagehandlersstage/onconversionfailed)(Action&lt;ConvertedPageContext, Exception&gt;) | Registreert een callback die wordt aangeroepen wanneer een paginaconversie mislukt. Opnieuw aanroepen vervangt elke eerder ingestelde handler. |

### Zie ook

* interface [IConversionConvertOrCompress](../iconversionconvertorcompress)
* namespace [GroupDocs.Conversion.Fluent](../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
