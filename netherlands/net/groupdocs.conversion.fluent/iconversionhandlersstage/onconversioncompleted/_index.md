---
title: "OnConversionCompleted"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Registreert een callback die wordt aangeroepen wanneer een documentconversie succesvol wordt voltooid. Opnieuw aanroepen vervangt elke eerder ingestelde handler."
type: docs
weight: 10
url: /nl/net/groupdocs.conversion.fluent/iconversionhandlersstage/onconversioncompleted/
---
## IConversionHandlersStage.OnConversionCompleted method

Registreert een callback die wordt aangeroepen wanneer een documentconversie succesvol wordt voltooid. Opnieuw aanroepen vervangt elke eerder ingestelde handler.

```csharp
public IConversionHandlersStage OnConversionCompleted(Action<ConvertedContext> onCompleted)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| onCompleted | Action`1 | Een actie om de voltooiing af te handelen, waarbij de conversie‑context wordt ontvangen. |

### Retourwaarde

Deze fase, zodat extra handlers of `Convert` / `Compress` kunnen worden gekoppeld.

### Zie ook

* class [ConvertedContext](../../../groupdocs.conversion/convertedcontext)
* interface [IConversionHandlersStage](../../iconversionhandlersstage)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
