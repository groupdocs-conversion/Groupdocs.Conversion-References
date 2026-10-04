---
title: "OnConversionFailed"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Registrerar en återuppringning som ska anropas när en dokumentkonvertering misslyckas. Återanrop ersätter eventuellt tidigare inställd hanterare."
type: docs
weight: 20
url: /sv/net/groupdocs.conversion.fluent/iconversionhandlersstage/onconversionfailed/
---
## IConversionHandlersStage.OnConversionFailed method

Registrerar en återuppringning som ska anropas när en dokumentkonvertering misslyckas. Återanrop ersätter eventuellt tidigare inställd hanterare.

```csharp
public IConversionHandlersStage OnConversionFailed(Action<ConvertedContext, Exception> onFailed)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| onFailed | Action`2 | En åtgärd för att hantera felet, som tar emot konverteringskontexten och undantaget som orsakade felet. |

### Returvärde

Detta steg, så att ytterligare hanterare eller `Convert` / `Compress` kan kedjas.

### Se även

* class [ConvertedContext](../../../groupdocs.conversion/convertedcontext)
* interface [IConversionHandlersStage](../../iconversionhandlersstage)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
