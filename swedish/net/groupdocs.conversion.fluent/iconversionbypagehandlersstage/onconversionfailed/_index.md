---
title: "OnConversionFailed"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Registrerar en återuppringning som ska anropas när en sidkonvertering misslyckas. Återanrop ersätter eventuellt tidigare inställd hanterare."
type: docs
weight: 20
url: /sv/net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/onconversionfailed/
---
## IConversionByPageHandlersStage.OnConversionFailed method

Registrerar en återuppringning som ska anropas när en sidkonvertering misslyckas. Återanrop ersätter eventuellt tidigare inställd hanterare.

```csharp
public IConversionByPageHandlersStage OnConversionFailed(
    Action<ConvertedPageContext, Exception> onFailed)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| onFailed | Action`2 | En åtgärd för att hantera felet, som tar emot den konverterade sidkontexten och undantaget som orsakade felet. |

### Returvärde

Detta steg, så att ytterligare hanterare eller `Convert` / `Compress` kan kedjas.

### Se även

* class [ConvertedPageContext](../../../groupdocs.conversion/convertedpagecontext)
* interface [IConversionByPageHandlersStage](../../iconversionbypagehandlersstage)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
