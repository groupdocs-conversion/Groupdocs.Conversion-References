---
title: "OnConversionCompleted"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Registrerar en återuppringning som ska anropas när en dokumentkonvertering slutförs framgångsrikt. Återanrop ersätter eventuellt tidigare inställd hanterare."
type: docs
weight: 10
url: /sv/net/groupdocs.conversion.fluent/iconversionhandlersstage/onconversioncompleted/
---
## IConversionHandlersStage.OnConversionCompleted method

Registrerar en återuppringning som ska anropas när en dokumentkonvertering slutförs framgångsrikt. Återanrop ersätter eventuellt tidigare inställd hanterare.

```csharp
public IConversionHandlersStage OnConversionCompleted(Action<ConvertedContext> onCompleted)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| onCompleted | Action`1 | En åtgärd för att hantera slutförandet, som tar emot konverteringskontexten. |

### Returvärde

Detta steg, så att ytterligare hanterare eller `Convert` / `Compress` kan kedjas.

### Se även

* class [ConvertedContext](../../../groupdocs.conversion/convertedcontext)
* interface [IConversionHandlersStage](../../iconversionhandlersstage)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
