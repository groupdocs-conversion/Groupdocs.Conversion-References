---
title: "OnConversionFailed"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Registreert een callback die wordt aangeroepen wanneer een paginaconversie mislukt. Opnieuw aanroepen vervangt elke eerder ingestelde handler."
type: docs
weight: 20
url: /nl/net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/onconversionfailed/
---
## IConversionByPageHandlersStage.OnConversionFailed method

Registreert een callback die wordt aangeroepen wanneer een paginaconversie mislukt. Opnieuw aanroepen vervangt elke eerder ingestelde handler.

```csharp
public IConversionByPageHandlersStage OnConversionFailed(
    Action<ConvertedPageContext, Exception> onFailed)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| onFailed | Action`2 | Een actie om de fout af te handelen, waarbij de geconverteerde paginacontext en de uitzondering die de fout veroorzaakte worden ontvangen. |

### Retourwaarde

Deze fase, zodat extra handlers of `Convert` / `Compress` kunnen worden gekoppeld.

### Zie ook

* class [ConvertedPageContext](../../../groupdocs.conversion/convertedpagecontext)
* interface [IConversionByPageHandlersStage](../../iconversionbypagehandlersstage)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
