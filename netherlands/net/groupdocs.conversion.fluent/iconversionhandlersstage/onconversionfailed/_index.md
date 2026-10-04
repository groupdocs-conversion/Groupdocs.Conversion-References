---
title: "OnConversionFailed"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Registreert een callback die wordt aangeroepen wanneer een documentconversie mislukt. Opnieuw aanroepen vervangt elke eerder ingestelde handler."
type: docs
weight: 20
url: /nl/net/groupdocs.conversion.fluent/iconversionhandlersstage/onconversionfailed/
---
## IConversionHandlersStage.OnConversionFailed method

Registreert een callback die wordt aangeroepen wanneer een documentconversie mislukt. Opnieuw aanroepen vervangt elke eerder ingestelde handler.

```csharp
public IConversionHandlersStage OnConversionFailed(Action<ConvertedContext, Exception> onFailed)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| onFailed | Action`2 | Een actie om de fout af te handelen, waarbij de conversie‑context en de uitzondering die de fout veroorzaakte worden ontvangen. |

### Retourwaarde

Deze fase, zodat extra handlers of `Convert` / `Compress` kunnen worden gekoppeld.

### Zie ook

* class [ConvertedContext](../../../groupdocs.conversion/convertedcontext)
* interface [IConversionHandlersStage](../../iconversionhandlersstage)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
